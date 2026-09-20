<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adm_kkbuq.css';
import '../../css/h/hffq3ijlx.css';
import '../../css/t/tjw051bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="adm_kkbuq"/><path class="hffq3ijlx"/><path clip-rule="evenodd" class="tjw051bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:file-plus-circle" /></template>
