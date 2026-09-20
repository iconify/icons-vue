<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leymwlb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="leymwlb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:data-screen-outline" /></template>
