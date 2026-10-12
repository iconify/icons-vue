<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-te0_bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o-te0_bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bookmark-fill-20" /></template>
