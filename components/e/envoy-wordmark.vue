<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exgu2ir-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="exgu2ir-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:envoy-wordmark" /></template>
