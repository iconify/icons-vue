<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k42c7bcyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k42c7bcyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:inbox-full" /></template>
