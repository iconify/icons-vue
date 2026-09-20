<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gttkkubpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gttkkubpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:double-venus" /></template>
