<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymekm1b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymekm1b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:lock" /></template>
