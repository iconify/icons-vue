<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7iw6bc4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m7iw6bc4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bowling-alley-15" /></template>
