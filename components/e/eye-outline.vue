<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/q/qf_wqd7nc.css';
import '../../css/k/ktu665dou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="qf_wqd7nc"/><path class="ktu665dou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:eye-outline" /></template>
