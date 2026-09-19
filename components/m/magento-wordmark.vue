<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk-q5i3tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gk-q5i3tl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:magento-wordmark" /></template>
