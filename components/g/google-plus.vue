<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtt8x7bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-5.5};
const content = `<path class="gtt8x7bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:google-plus" /></template>
