<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzargkbqk.css';
import '../../css/f/f11z55kqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzargkbqk"/><path class="f11z55kqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:chart-pie-alt-solid" /></template>
