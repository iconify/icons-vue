<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb78fs52v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb78fs52v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:forward" /></template>
