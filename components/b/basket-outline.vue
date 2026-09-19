<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2g2swbim.css';
import '../../css/f/f471phb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d2g2swbim"/><path class="f471phb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:basket-outline" /></template>
