<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3jvhdbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="r3jvhdbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:action-undo" /></template>
