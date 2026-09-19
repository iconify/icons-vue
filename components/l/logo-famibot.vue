<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5mhyjbwd.css';
import '../../css/t/tq10f7bbh.css';
import '../../css/h/h-e9_jbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y5mhyjbwd"/><path class="tq10f7bbh"/><path class="h-e9_jbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-famibot" /></template>
