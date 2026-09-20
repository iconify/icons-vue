<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuw50bchd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuw50bchd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:element-plus-filled" /></template>
