<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnt80_bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnt80_bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beard-fill" /></template>
