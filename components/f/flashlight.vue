<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agh1_fbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="agh1_fbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:flashlight" /></template>
