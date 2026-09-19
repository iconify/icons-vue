<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlryto17e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="nlryto17e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:magazine" /></template>
