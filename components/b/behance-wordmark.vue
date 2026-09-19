<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkp81t-cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dkp81t-cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:behance-wordmark" /></template>
