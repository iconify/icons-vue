<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8yruddxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u8yruddxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:k3os-wordmark" /></template>
