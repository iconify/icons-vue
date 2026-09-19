<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knjor4pcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knjor4pcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:fast-forward" /></template>
