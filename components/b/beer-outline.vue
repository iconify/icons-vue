<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5xxtl4yd.css';
import '../../css/n/nuhx_m9bs.css';
import '../../css/r/r1lz3zb-k.css';
import '../../css/g/gd5-xc8zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t5xxtl4yd"/><path class="nuhx_m9bs"/><path class="r1lz3zb-k"/><path class="gd5-xc8zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:beer-outline" /></template>
