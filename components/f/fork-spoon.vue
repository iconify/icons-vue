<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2mfpbxly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2mfpbxly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fork-spoon" /></template>
