<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s6_hgo1gh.css';
import '../../css/d/d-q9u0ozl.css';
import '../../css/w/wom5eac6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s6_hgo1gh"/><path class="d-q9u0ozl"/><path class="wom5eac6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gamepad" /></template>
