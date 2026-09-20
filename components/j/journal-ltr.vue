<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgxqd4air.css';
import '../../css/z/zczqr0djk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lgxqd4air"/><path class="zczqr0djk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:journal-ltr" /></template>
