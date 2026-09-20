<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf1-a4a-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uf1-a4a-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:attachement-16" /></template>
