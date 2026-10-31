<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob20kwbzk.css';
import '../../css/l/l1kbw1b1l.css';
import '../../css/x/x0hxdhfls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ob20kwbzk"/><path class="l1kbw1b1l"/><path class="x0hxdhfls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:iceland" /></template>
