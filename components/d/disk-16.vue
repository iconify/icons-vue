<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chj_3ab-w.css';
import '../../css/v/v97disbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="chj_3ab-w"/><path clip-rule="evenodd" class="v97disbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:disk-16" /></template>
