<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trxi2bbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trxi2bbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-top-right-filled" /></template>
