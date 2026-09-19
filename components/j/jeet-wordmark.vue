<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjid91ngn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wjid91ngn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jeet-wordmark" /></template>
