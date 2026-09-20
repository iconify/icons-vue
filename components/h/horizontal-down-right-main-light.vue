<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6hc4yeog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6hc4yeog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:horizontal-down-right-main-light" /></template>
