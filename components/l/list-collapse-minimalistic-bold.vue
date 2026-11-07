<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_kzq_bzg.css';
import '../../css/x/xgkgwx6vp.css';
import '../../css/a/ax17gbbek.css';
import '../../css/t/t5ovb-bau.css';
import '../../css/j/jctsgpbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_kzq_bzg"/><path class="xgkgwx6vp"/><path class="ax17gbbek"/><path class="t5ovb-bau"/><path class="jctsgpbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-collapse-minimalistic-bold" /></template>
