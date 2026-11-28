<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9e_3fb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9e_3fb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-medical-clock" /></template>
