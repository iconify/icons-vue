<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt17g7bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt17g7bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-lens" /></template>
