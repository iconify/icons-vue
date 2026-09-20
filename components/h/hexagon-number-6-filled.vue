<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh1m32rea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh1m32rea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-number-6-filled" /></template>
