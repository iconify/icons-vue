<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rose2n_gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rose2n_gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkbox-marked-circle" /></template>
