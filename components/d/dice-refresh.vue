<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4n29ob_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4n29ob_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:dice-refresh" /></template>
