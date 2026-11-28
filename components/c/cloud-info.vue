<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl34nzb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl34nzb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cloud-info" /></template>
