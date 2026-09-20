<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqa_orb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sqa_orb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:ie9" /></template>
