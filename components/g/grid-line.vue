<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oblef_bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oblef_bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:grid-line" /></template>
