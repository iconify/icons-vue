<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhlnukb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhlnukb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bazarr" /></template>
