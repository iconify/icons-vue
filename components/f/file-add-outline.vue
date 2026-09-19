<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx_lz50_l.css';
import '../../css/l/l2nst-b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx_lz50_l"/><path class="l2nst-b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:file-add-outline" /></template>
