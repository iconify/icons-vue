<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy2bf7d2l.css';
import '../../css/x/xr0hl1ndv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xy2bf7d2l"/><path class="xr0hl1ndv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-quality-20" /></template>
