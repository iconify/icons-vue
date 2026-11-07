<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gde1vd8ly.css';
import '../../css/m/miik5gboc.css';
import '../../css/m/m8_v07a_t.css';
import '../../css/w/wewvnfb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gde1vd8ly"/><path class="miik5gboc"/><path class="m8_v07a_t"/><path class="wewvnfb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-open-bold" /></template>
