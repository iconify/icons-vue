<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj_qicchw.css';
import '../../css/m/mgkbe6uxk.css';
import '../../css/i/i7sr6ubzr.css';
import '../../css/g/g3gxxib9z.css';
import '../../css/s/sdj3236vq.css';
import '../../css/a/a8a4agb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj_qicchw"/><path class="mgkbe6uxk"/><path class="i7sr6ubzr"/><path class="g3gxxib9z"/><path class="sdj3236vq"/><path class="a8a4agb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-scheduler" /></template>
