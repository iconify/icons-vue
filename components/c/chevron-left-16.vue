<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd795fxhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xd795fxhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-left-16" /></template>
