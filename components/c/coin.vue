<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tay3aacfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tay3aacfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:coin" /></template>
