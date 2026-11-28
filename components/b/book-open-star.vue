<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxuv1pb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxuv1pb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:book-open-star" /></template>
