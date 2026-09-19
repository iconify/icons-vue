<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0bv6ac3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c0bv6ac3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:download2" /></template>
