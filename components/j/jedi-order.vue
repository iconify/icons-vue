<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmw6wmnpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wmw6wmnpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:jedi-order" /></template>
