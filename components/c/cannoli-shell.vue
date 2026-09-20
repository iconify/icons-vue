<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz6ef4bsh.css';
import '../../css/u/uqdpf65ef.css';
import '../../css/j/jf5jiy4cv.css';
import '../../css/t/tpdj2bgpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wz6ef4bsh"/><circle class="uqdpf65ef"/><path class="jf5jiy4cv"/><path class="tpdj2bgpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cannoli-shell" /></template>
