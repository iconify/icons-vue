<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuxnpbbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zuxnpbbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:glasses-16" /></template>
