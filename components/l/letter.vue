<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzjz2-bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="bzjz2-bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:letter" /></template>
