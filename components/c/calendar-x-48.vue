<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pycxs8orj.css';
import '../../css/x/xjuhbqb1b.css';
import '../../css/l/l3lpevbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pycxs8orj"/><path class="xjuhbqb1b"/><path class="l3lpevbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-x-48" /></template>
