<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plt19qbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plt19qbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bed" /></template>
