<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbp-kxkda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbp-kxkda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:link-check" /></template>
