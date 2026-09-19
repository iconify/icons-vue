<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq6wx1c7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq6wx1c7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cat-filled" /></template>
