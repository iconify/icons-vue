<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f0xsko-4b.css';
import '../../css/g/guqhbex6p.css';
import '../../css/s/s1kut8o6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f0xsko-4b"/><path class="guqhbex6p wm-a"/><path class="s1kut8o6j wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-alien" /></template>
