<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwal6xeof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gwal6xeof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:cheveron-up" /></template>
