<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmfh31bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cmfh31bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-slash-fill" /></template>
