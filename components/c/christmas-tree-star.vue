<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkrk-nb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkrk-nb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:christmas-tree-star" /></template>
