<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppr3nnzrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppr3nnzrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:cursor" /></template>
