<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhhygvs3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bhhygvs3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bookmark-simple-plus-light" /></template>
