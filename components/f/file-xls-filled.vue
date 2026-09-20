<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opjqw8bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="opjqw8bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-xls-filled" /></template>
