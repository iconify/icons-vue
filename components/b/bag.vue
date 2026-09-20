<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agdxem1im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="agdxem1im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bag" /></template>
