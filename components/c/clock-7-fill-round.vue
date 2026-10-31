<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucscbx4hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucscbx4hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-7-fill-round" /></template>
