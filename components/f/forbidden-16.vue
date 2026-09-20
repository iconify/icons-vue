<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvr_jqvun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tvr_jqvun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:forbidden-16" /></template>
