<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fftuk_bwd.css';
import '../../css/a/ascdhq43i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fftuk_bwd"/><path class="ascdhq43i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:ecology-global-warming-globe" /></template>
