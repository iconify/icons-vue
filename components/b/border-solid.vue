<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhwk81qdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fhwk81qdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:border-solid" /></template>
