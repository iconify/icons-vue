<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqr-nobad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqr-nobad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:align-center" /></template>
