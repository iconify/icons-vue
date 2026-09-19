<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rin3p3brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rin3p3brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:briefcase" /></template>
