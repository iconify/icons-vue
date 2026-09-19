<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo4chr_jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo4chr_jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:data" /></template>
