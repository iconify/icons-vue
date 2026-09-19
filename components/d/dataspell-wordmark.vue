<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d00cv9bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="d00cv9bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:dataspell-wordmark" /></template>
