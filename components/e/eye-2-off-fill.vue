<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw_js72hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw_js72hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eye-2-off-fill" /></template>
