<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js_s7u-5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":77,"height":649};
const content = `<path class="js_s7u-5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:colon" /></template>
