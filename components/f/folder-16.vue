<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw0cr8vxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fw0cr8vxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:folder-16" /></template>
