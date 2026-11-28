<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si-995bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si-995bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:image-check" /></template>
