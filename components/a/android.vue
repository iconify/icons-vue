<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2_trcbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u2_trcbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:android" /></template>
