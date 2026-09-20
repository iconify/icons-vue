<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2jo_5btr.css';
import '../../css/m/muf1bphxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="f2jo_5btr"/><path class="muf1bphxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:loading-3-fill" /></template>
