<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gmk1bhgwk.css';
import '../../css/g/gum7tibxa.css';
import '../../css/r/rmlatf6un.css';
import '../../css/i/i0ecgc6dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gmk1bhgwk"/><path class="gum7tibxa"/><path class="rmlatf6un"/><path class="i0ecgc6dl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:canvas" /></template>
