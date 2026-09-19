<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc2lzsb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc2lzsb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:like" /></template>
