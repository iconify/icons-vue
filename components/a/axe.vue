<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meo_3-l_k.css';
import '../../css/d/d4tgy6_gn.css';
import '../../css/l/lvwy1yo9v.css';
import '../../css/i/iuph7tb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meo_3-l_k"/><path class="d4tgy6_gn"/><path class="lvwy1yo9v"/><path class="iuph7tb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:axe" /></template>
