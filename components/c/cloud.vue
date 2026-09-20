<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcb7wmksb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcb7wmksb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:cloud" /></template>
