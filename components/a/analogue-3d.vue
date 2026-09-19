<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfr3i41sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfr3i41sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:analogue-3d" /></template>
