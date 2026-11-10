<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slbc6rgwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="slbc6rgwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:heart-slash-16-solid" /></template>
