<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkmuvyw1o.css';
import '../../css/a/a_ls9acgf.css';
import '../../css/n/nu2_-nbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="xkmuvyw1o"/><path class="a_ls9acgf"/><path class="nu2_-nbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-hazard" /></template>
