<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-0aukb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b-0aukb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mac-option" /></template>
