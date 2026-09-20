<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/podgzbc_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="podgzbc_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:chalk" /></template>
