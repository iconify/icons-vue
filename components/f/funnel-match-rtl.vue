<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biuihtbcw.css';
import '../../css/n/nou84c3ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="biuihtbcw"/><path class="nou84c3ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:funnel-match-rtl" /></template>
