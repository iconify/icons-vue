<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou6jo2k2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ou6jo2k2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:alphabet" /></template>
