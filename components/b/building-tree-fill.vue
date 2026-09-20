<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d46e2yb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d46e2yb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:building-tree-fill" /></template>
