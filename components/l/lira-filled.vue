<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz3iy2bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz3iy2bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lira-filled" /></template>
