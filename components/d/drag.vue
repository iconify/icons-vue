<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvge1vtpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvge1vtpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:drag" /></template>
