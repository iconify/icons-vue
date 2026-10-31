<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsja-j37j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsja-j37j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hotel-gloss" /></template>
