<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3teuyc5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t3teuyc5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:heart-solid" /></template>
