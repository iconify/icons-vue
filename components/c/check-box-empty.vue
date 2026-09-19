<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_nmbcf5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":448};
const content = `<path class="s_nmbcf5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:check-box-empty" /></template>
