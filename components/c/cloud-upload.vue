<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9pi0vxzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9pi0vxzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:cloud-upload" /></template>
