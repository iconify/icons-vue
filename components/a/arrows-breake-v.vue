<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j88i-bbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j88i-bbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-breake-v" /></template>
