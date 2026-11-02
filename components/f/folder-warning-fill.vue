<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wld98je9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wld98je9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-warning-fill" /></template>
