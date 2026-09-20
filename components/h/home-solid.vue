<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s155mt1fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s155mt1fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:home-solid" /></template>
