<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcwm9zbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcwm9zbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cloud-moon" /></template>
