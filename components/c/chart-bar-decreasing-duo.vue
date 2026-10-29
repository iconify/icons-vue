<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f4so9hbwp.css';
import '../../css/s/skn8acc-z.css';
import '../../css/c/c0bw40ovn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f4so9hbwp"/><path class="skn8acc-z wm-a"/><path class="c0bw40ovn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-bar-decreasing-duo" /></template>
