<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6n136b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v6n136b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:adobe-typekit" /></template>
