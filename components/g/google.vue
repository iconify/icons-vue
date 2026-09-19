<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq-4k7bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zq-4k7bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:google" /></template>
