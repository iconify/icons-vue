<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl891nbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl891nbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-drop-up" /></template>
