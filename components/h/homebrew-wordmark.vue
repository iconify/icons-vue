<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqzmu0bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qqzmu0bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:homebrew-wordmark" /></template>
