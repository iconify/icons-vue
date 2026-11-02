<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvrvn9blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvrvn9blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alert-fill" /></template>
