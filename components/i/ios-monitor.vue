<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5_4c5bns.css';
import '../../css/t/tvqwrac8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c5_4c5bns"/><path class="tvqwrac8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-monitor" /></template>
