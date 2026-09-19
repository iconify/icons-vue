<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drjns0whf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drjns0whf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-stripe" /></template>
