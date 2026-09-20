<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yozvh-bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yozvh-bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hello" /></template>
