<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4h3a_bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c4h3a_bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:jack-16" /></template>
