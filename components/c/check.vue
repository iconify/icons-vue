<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r96o9m0kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="r96o9m0kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:check" /></template>
