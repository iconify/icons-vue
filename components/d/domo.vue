<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si58bs_sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si58bs_sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:domo" /></template>
