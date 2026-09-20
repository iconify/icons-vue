<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="iewpqupxy"><path class="y_jk8c7cj"/><path class="wt40adb9z"/><path class="c58stfsgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bat" /></template>
<style>
.c58stfsgh {
  d: path("M20.943 19.608L15.7 16.8H8.3l-5.245 2.808a.4.4 0 0 0 .152.14a.44.44 0 0 0 .207.052h17.17a.44.44 0 0 0 .208-.052a.4.4 0 0 0 .152-.14");
}

.iewpqupxy {
  fill: var(--svg-color--ff4724, #ff4724);
}

.wt40adb9z {
  d: path("M20.943 19.184L12.358 4.406A.42.42 0 0 0 12 4.2l.001 6l3.694 6.611l5.25 2.788a.41.41 0 0 0-.001-.415");
}

.y_jk8c7cj {
  d: path("M12 4.2a.41.41 0 0 0-.358.207L3.056 19.184a.41.41 0 0 0 0 .414l5.24-2.8l3.705-6.6z");
}

</style>
