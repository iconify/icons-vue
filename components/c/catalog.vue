<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7sr6ubzr.css';
import '../../css/c/c9x03gb1i.css';
import '../../css/d/dp0am7bls.css';
import '../../css/p/pn5a3ub8d.css';
import '../../css/n/n-96atbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ubzr"/><path class="c9x03gb1i"/><path class="dp0am7bls"/><path class="pn5a3ub8d"/><path class="n-96atbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:catalog" /></template>
