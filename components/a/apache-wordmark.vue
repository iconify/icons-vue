<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc41zybcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="sc41zybcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:apache-wordmark" /></template>
