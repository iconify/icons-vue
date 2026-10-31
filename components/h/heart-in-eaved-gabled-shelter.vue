<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-k6ywuma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g-k6ywuma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-in-eaved-gabled-shelter" /></template>
