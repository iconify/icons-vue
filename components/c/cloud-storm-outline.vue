<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph-lyk__x.css';
import '../../css/y/ybkhrgori.css';
import '../../css/n/n_7s633jr.css';
import '../../css/o/onh9oyipx.css';
import '../../css/m/mgjb77b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph-lyk__x"/><path class="ybkhrgori"/><path class="n_7s633jr"/><path class="onh9oyipx"/><path class="mgjb77b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-storm-outline" /></template>
