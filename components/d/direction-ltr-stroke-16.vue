<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnwwgetvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wnwwgetvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:direction-ltr-stroke-16" /></template>
