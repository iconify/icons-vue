<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du2f62gcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du2f62gcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flower-5-line" /></template>
