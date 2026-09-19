<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thghjjkzc.css';
import '../../css/x/x97ig8bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="thghjjkzc"/><path class="x97ig8bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:k3s-wordmark" /></template>
