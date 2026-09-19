<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4r4kjkia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x4r4kjkia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:folder-plus" /></template>
