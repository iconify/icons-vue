<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1x_6zbkv.css';
import '../../css/t/ty0x_qewu.css';
import '../../css/a/aqt2kdbol.css';
import '../../css/w/w36ns7bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="ty0x_qewu"/><path class="aqt2kdbol"/><path class="w36ns7bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:lesotho" /></template>
