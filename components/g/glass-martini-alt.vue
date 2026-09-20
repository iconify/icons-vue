<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvpz_acxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvpz_acxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:glass-martini-alt" /></template>
