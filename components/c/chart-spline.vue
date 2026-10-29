<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqiql6y-e.css';
import '../../css/p/p5hpsnbhe.css';
import '../../css/i/iub1qbb_k.css';
import '../../css/n/nc1z8tb5e.css';
import '../../css/f/f6h5bybck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqiql6y-e wm-shadow"/><path class="p5hpsnbhe wm-k"/><path class="iub1qbb_k wm-k"/><path class="nc1z8tb5e wm-a"/><path class="f6h5bybck wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:chart-spline" /></template>
