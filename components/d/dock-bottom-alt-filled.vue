<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6i1a4bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6i1a4bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-bottom-alt-filled" /></template>
