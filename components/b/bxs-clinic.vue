<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr0bdwb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr0bdwb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-clinic" /></template>
