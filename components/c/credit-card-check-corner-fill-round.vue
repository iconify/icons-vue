<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9gh00b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9gh00b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-check-corner-fill-round" /></template>
