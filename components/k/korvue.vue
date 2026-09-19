<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bflich7ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bflich7ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:korvue" /></template>
