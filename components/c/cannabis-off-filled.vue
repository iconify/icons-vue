<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zve1wfbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zve1wfbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cannabis-off-filled" /></template>
