<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuyvh2sic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuyvh2sic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:archive-of-our-own" /></template>
