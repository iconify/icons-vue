<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thlhudbvm.css';
import '../../css/u/ugbw2eb3a.css';
import '../../css/l/le_-26bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thlhudbvm"/><path class="ugbw2eb3a"/><path class="le_-26bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ltx" /></template>
