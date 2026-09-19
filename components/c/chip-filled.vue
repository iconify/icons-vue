<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1t1bndoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1t1bndoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chip-filled" /></template>
