<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arebbvaap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="arebbvaap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:align-left" /></template>
