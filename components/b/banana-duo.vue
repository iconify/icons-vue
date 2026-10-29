<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hol610bkj.css';
import '../../css/v/vxyac5iur.css';
import '../../css/o/ow5u1cc8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hol610bkj"/><path class="vxyac5iur wm-a"/><path class="ow5u1cc8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:banana-duo" /></template>
