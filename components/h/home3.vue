<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lybe10l9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lybe10l9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:home3" /></template>
