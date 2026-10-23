<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zucb4acff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zucb4acff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-center-horizontal" /></template>
