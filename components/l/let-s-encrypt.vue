<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/votzz4x_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="votzz4x_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:let-s-encrypt" /></template>
