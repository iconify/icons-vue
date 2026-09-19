<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbgfdabov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbgfdabov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:fast-rewind" /></template>
