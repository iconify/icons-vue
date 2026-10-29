<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o63jc9t6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o63jc9t6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-sketch" /></template>
