<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se96s_brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloudy-night" /></template>
<style>
.se96s_brz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.72 7.847q-.88 1.247-1.092 2.628q1.295-1.34 3.471-1.581q3.429-.381 5.32 2.374q1.492.133 2.586 1.227Q22.25 13.74 22.25 15.5t-1.245 3.005T18 19.75H9q-3.615 0-3.745-3.484q-3.851-4.999.098-10.044q4.029-5.149 9.962-2.403q.087.041.161.102t.131.138t.091.168q.035.089.047.184q.008.074.003.147q-.006.074-.026.145t-.054.137q-.033.066-.079.124q-.045.058-.102.106t-.12.084q-.065.036-.135.059t-.143.032q-2.764.328-4.369 2.602m-5.115 6.2q.654-1.471 2.513-1.738q-.357-2.871 1.377-5.327q1.194-1.691 2.904-2.515q-3.376-.501-5.865 2.679q-2.711 3.464-.929 6.901");
}

</style>
