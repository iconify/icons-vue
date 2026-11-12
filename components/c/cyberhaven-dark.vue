<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceqg47lfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ceqg47lfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cyberhaven-dark" /></template>
