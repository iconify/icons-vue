<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/viaa6ubuw.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/x/xprwyhbwt.css';
import '../../css/k/ks7bf8bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="viaa6ubuw"/><circle class="shu3xdl9q"/><circle class="xprwyhbwt"/><path class="ks7bf8bjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bacteria" /></template>
