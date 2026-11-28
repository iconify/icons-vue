<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6s329bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6s329bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-tree-solid" /></template>
