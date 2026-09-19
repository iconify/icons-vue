<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t9slfgb9y"/><path class="s_ed1_vwq"/><path class="y7nst5zka"/><path class="n01podizv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bakalari-online" /></template>
<style>
.n01podizv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.522 21.198v5.365l3.79 2.204m4.706-12.352l.137 5.364l-3.768 2.153");
}

.s_ed1_vwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.069 8.898l-13.156 7.449V31.38l12.95 7.653l13.292-7.722l-.137-5.261l-8.496-4.852l8.496-4.783z");
}

.t9slfgb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.932 3.5L6.186 13.682v20.431L23.863 44.5l17.883-10.523l.068-20.158z");
}

.y7nst5zka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.177 19.14l-8.314-4.843l-8.29 4.783l-.206 9.567L24 33.567l13.018-7.517");
}

</style>
