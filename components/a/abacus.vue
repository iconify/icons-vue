<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_2rjb56q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_2rjb56q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:abacus" /></template>
