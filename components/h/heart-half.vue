<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssm45ytaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ssm45ytaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-half" /></template>
