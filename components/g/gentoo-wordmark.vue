<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrib8bc3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hrib8bc3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gentoo-wordmark" /></template>
