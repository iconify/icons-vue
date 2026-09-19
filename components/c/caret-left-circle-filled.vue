<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnxh3obsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnxh3obsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-left-circle-filled" /></template>
