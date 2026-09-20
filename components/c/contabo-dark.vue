<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g69cwyy3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g69cwyy3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:contabo-dark" /></template>
