<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2t6debfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2t6debfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:carrot-filled" /></template>
