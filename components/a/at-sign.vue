<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_z2cvb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_z2cvb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:at-sign" /></template>
