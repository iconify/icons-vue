<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_yv9lbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_yv9lbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-right-square-line" /></template>
