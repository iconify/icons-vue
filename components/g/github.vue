<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbt5g2ela.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cbt5g2ela"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:github" /></template>
