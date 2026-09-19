<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx6l2l7vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dx6l2l7vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:heroku-wordmark" /></template>
