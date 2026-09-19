<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xndgo8bxx.css';
import '../../css/d/dj23tuv2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xndgo8bxx"/><path class="dj23tuv2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:gnuradio-wordmark" /></template>
