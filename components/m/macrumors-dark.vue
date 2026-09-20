<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhoq_e62f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bhoq_e62f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:macrumors-dark" /></template>
