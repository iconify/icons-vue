<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxz3oytdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qxz3oytdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:djangorest-wordmark" /></template>
