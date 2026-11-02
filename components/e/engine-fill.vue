<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_3_xbc0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_3_xbc0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:engine-fill" /></template>
