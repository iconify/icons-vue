<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz_6fthyk.css';
import '../../css/p/p6qekmbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bz_6fthyk"/><path class="p6qekmbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:htmx-wordmark" /></template>
