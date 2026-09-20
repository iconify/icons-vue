<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc1v7n.css';
import '../../css/w/w5x6ze.css';
import '../../css/v/vmt83d.css';
import '../../css/m/mfx1yn.css';
import '../../css/p/pij0sj.css';
import '../../css/i/i6qhvc.css';
import '../../css/a/ashj5r.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-28.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc1v7n w5x6ze"/><path class="vmt83d w5x6ze"/><path class="mfx1yn w5x6ze"/><path class="pij0sj w5x6ze"/><path class="i6qhvc w5x6ze"/><path class="ashj5r w5x6ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:list-3-twotone" /></template>
