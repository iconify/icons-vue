<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-t5xollv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-t5xollv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:flask-empty" /></template>
