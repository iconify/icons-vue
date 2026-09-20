<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcpth-wqs.css';
import '../../css/l/lx7mkia0m.css';
import '../../css/h/hkc780bsc.css';
import '../../css/p/pkssvg6_z.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wcpth-wqs"/><path class="lx7mkia0m"/><path class="hkc780bsc"/><path class="pkssvg6_z"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-guinea-bissau" /></template>
