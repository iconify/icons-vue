<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/norve6ahi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="norve6ahi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ionic" /></template>
