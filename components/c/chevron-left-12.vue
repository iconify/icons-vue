<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdxi4ubed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="qdxi4ubed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-left-12" /></template>
