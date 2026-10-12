<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hchrethjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hchrethjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-tree-filled" /></template>
