<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl0_qcqck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xl0_qcqck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fire-square" /></template>
