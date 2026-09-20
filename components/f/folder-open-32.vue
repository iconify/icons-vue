<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_jj1gxap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="d_jj1gxap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:folder-open-32" /></template>
