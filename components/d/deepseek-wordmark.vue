<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv1wov0db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pv1wov0db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:deepseek-wordmark" /></template>
