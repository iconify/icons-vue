<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn5rgey5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn5rgey5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:grid-lines" /></template>
