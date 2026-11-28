<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymzoa8clr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hise5gb9x.css';
import '../../css/b/bktrjnn5f.css';
import '../../css/v/vv4lo6b2m.css';
import '../../css/n/nvwd6n36m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary ymzoa8clr"/><g class="dt0cm9dhy primary"><path class="hise5gb9x"/><path class="bktrjnn5f"/><path class="vv4lo6b2m"/><path class="nvwd6n36m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:landmark-duo" /></template>
