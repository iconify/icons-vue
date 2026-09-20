<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea0phfbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ea0phfbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cheese" /></template>
