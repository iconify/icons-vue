<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd0l9kb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="gd0l9kb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:android" /></template>
