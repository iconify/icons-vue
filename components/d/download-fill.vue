<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhufd2bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhufd2bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:download-fill" /></template>
