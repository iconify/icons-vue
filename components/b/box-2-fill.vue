<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz3i1ib_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz3i1ib_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:box-2-fill" /></template>
