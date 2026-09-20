<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekj6e4b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekj6e4b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kinsta" /></template>
