<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5yjr_spk.css';
import '../../css/p/p075md36j.css';
import '../../css/l/ldzer7b8d.css';
import '../../css/h/hz4bs5lpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="q5yjr_spk"/><path class="p075md36j"/><path class="ldzer7b8d"/><path class="hz4bs5lpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:kiribati" /></template>
