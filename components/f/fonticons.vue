<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9v8zkb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="o9v8zkb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:fonticons" /></template>
