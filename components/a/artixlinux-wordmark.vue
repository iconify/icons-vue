<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbqrb3a2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sbqrb3a2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:artixlinux-wordmark" /></template>
