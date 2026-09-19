<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f99-2obxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f99-2obxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:cypressio-wordmark" /></template>
