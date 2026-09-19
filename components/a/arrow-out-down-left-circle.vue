<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2k-5lb6a.css';
import '../../css/j/jbyiw1r0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2k-5lb6a"/><path class="jbyiw1r0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-left-circle" /></template>
