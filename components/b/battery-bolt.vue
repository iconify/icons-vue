<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up4gwh-bs.css';
import '../../css/u/uv693bcmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up4gwh-bs"/><path class="uv693bcmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:battery-bolt" /></template>
