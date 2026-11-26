<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwxydfe-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cwxydfe-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:binijs-wordmark" /></template>
