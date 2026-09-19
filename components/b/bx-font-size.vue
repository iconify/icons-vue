<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jks_f3kme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jks_f3kme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-font-size" /></template>
