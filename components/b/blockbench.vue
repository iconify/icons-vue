<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv3lw8b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv3lw8b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:blockbench" /></template>
