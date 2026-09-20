<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdcad8bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:id-card-2-outline-sharp" /></template>
<style>
.bdcad8bgv {
  fill: currentColor;
  d: path("m7.45 12.427l3.102-3.102l-.627-.633l-2.5 2.5l-1.35-1.35l-.627.608zm-1.95 2.88H10v-.884H5.5zm6.116 0h6.615v-.165q0-.875-.879-1.354t-2.429-.48t-2.429.48t-.879 1.354zm4.374-4.048q.433-.434.433-1.067t-.433-1.066t-1.067-.434t-1.066.434t-.434 1.066t.434 1.067t1.066.433t1.067-.433M3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
