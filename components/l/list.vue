<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf3y1xrnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf3y1xrnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:list" /></template>
