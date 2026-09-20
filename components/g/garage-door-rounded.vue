<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahgs-jcnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:garage-door-rounded" /></template>
<style>
.ahgs-jcnd {
  fill: currentColor;
  d: path("M6.616 19.02q-.667 0-1.141-.475T5 17.404v-7.77h-.379q-.292 0-.379-.272t.137-.454l6.638-5.077q.449-.337.983-.337t.983.337l6.613 5.077q.223.18.137.454t-.38.273H19v7.769q0 .666-.475 1.14t-1.14.475zm1.711-.886h7.346V16.25H8.327zm0-2.769h7.346v-1.884H8.327zm0-2.769h7.346v-1.885H8.327zm3.683-4.615q.3 0 .51-.21t.21-.52t-.21-.521t-.52-.21q-.29 0-.51.21q-.22.209-.22.52t.22.52t.52.21");
}

</style>
