<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eboq2oy7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eboq2oy7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-left-circle-filled" /></template>
