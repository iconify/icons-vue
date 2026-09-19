<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjdzctb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qjdzctb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:apify-wordmark" /></template>
