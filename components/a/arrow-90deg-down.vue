<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgci88bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bgci88bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-90deg-down" /></template>
