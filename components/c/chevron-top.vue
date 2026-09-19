<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt0_y9e1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kt0_y9e1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:chevron-top" /></template>
