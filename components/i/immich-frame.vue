<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlx-9kbbc.css';
import '../../css/j/j9bg-6ovb.css';
import '../../css/q/q8gh54b1j.css';
import '../../css/e/ectfl7b1s.css';
import '../../css/p/p_z4wwf6p.css';
import '../../css/b/bbniey5_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mlx-9kbbc"/><path class="j9bg-6ovb"/><path class="q8gh54b1j"/><path class="ectfl7b1s"/><path class="p_z4wwf6p"/><path class="bbniey5_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:immich-frame" /></template>
