<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq4awzbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="rq4awzbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:library" /></template>
