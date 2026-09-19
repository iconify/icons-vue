<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlhh1586r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qlhh1586r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:building" /></template>
