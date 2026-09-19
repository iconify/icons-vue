<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5-xncc3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t5-xncc3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:dcr" /></template>
