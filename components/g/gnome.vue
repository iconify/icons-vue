<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/rs4_mfifm.css';
import '../../css/k/kcrc3hg8p.css';
import '../../css/s/seh1ydy_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rs4_mfifm"/><path class="kcrc3hg8p"/><path class="seh1ydy_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:gnome" /></template>
