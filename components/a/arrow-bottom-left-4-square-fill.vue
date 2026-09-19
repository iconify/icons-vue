<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvl_7yb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cvl_7yb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-4-square-fill" /></template>
