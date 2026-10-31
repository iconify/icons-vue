<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_u_7tbvg.css';
import '../../css/i/i71-ju5_c.css';
import '../../css/y/ytd2ngj_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n_u_7tbvg"/><path class="i71-ju5_c"/><path class="ytd2ngj_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:lemon" /></template>
