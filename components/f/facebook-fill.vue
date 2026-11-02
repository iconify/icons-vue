<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrpi9pbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrpi9pbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:facebook-fill" /></template>
