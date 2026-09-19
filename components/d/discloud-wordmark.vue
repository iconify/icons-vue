<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4cxb1bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l4cxb1bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:discloud-wordmark" /></template>
