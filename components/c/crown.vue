<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw6ek34qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iw6ek34qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:crown" /></template>
