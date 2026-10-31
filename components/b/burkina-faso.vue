<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx_xvr4ug.css';
import '../../css/y/y70x02bra.css';
import '../../css/l/lmzttacpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="wx_xvr4ug"/><path class="y70x02bra"/><path class="lmzttacpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:burkina-faso" /></template>
