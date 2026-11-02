<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-27el72i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-27el72i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:emergency-flashers-fill" /></template>
