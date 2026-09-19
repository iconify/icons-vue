<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx2-j8bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jx2-j8bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:bold" /></template>
