<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o48combuk.css';
import '../../css/m/m0bye0bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="o48combuk"/><path class="m0bye0bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:leaf-6" /></template>
