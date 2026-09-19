<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doh7t8rwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="doh7t8rwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:express-wordmark" /></template>
