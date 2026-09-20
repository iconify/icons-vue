<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwy_bs32g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kwy_bs32g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:arrow-outline-left" /></template>
