<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kc-lfrb0i.css';
import '../../css/f/fz9vu96sc.css';
import '../../css/w/way4u1f4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kc-lfrb0i"/><path class="fz9vu96sc"/><path class="way4u1f4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-setting" /></template>
