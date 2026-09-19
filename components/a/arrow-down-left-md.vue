<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfedjsbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfedjsbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-down-left-md" /></template>
