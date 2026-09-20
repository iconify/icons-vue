<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/pezxs9bin.css';
import '../../css/b/b10du-zvb.css';
import '../../css/f/fa3gx-2-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pezxs9bin"/><circle class="b10du-zvb"/><path class="fa3gx-2-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gear2" /></template>
