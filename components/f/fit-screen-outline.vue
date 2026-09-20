<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpes_5kab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kpes_5kab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:fit-screen-outline" /></template>
