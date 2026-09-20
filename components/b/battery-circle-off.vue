<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t5kuevs6k.css';
import '../../css/p/pgaah8bvy.css';
import '../../css/y/ypb3ww6cw.css';
import '../../css/m/mo5netbri.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><g transform="translate(3 3)"><rect class="t5kuevs6k"/><path class="pgaah8bvy"/><path clip-rule="evenodd" class="ypb3ww6cw"/><path class="mo5netbri"/></g><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:battery-circle-off" /></template>
