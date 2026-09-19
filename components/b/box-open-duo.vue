<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zsogtr9od.css';
import '../../css/k/km6852b-l.css';
import '../../css/c/cbp9c2buo.css';
import '../../css/f/fa29q174i.css';
import '../../css/w/wl67t95mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zsogtr9od"/><path class="km6852b-l"/><path class="cbp9c2buo"/><path class="fa29q174i"/><path class="wl67t95mi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-open-duo" /></template>
