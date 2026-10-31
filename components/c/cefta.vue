<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgbzj_rvw.css';
import '../../css/y/y862trbtu.css';
import '../../css/e/e11mdeprk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="fgbzj_rvw"/><path class="y862trbtu"/><path class="e11mdeprk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:cefta" /></template>
