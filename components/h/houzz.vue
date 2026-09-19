<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it41hmb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="it41hmb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:houzz" /></template>
