<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p64taib3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p64taib3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:heart-16" /></template>
