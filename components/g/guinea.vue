<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdhad0ihx.css';
import '../../css/b/bjhb_puya.css';
import '../../css/w/w4m-jwb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="qdhad0ihx"/><path class="bjhb_puya"/><path class="w4m-jwb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:guinea" /></template>
