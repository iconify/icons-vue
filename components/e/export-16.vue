<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr1tfnb7u.css';
import '../../css/g/gnwbtmb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xr1tfnb7u"/><path class="gnwbtmb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:export-16" /></template>
