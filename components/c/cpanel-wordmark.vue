<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzeot8bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vzeot8bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:cpanel-wordmark" /></template>
