<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zapq53rvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-drink-outline-sharp" /></template>
<style>
.zapq53rvt {
  fill: currentColor;
  d: path("M6.027 21L4 3h16l-2.008 18zm-.3-11.615L6.923 20h10.173l1.196-10.615zm-.135-1h12.835L18.866 4H5.116zm5.452 8.336q-.394-.394-.394-.955q0-.51.28-1.084t1.07-1.66q.79 1.086 1.07 1.66t.28 1.084q0 .561-.394.955t-.956.395t-.956-.395m2.625.714q.681-.681.681-1.67q0-.794-.48-1.696T12 11.385q-1.39 1.782-1.87 2.684t-.48 1.697q0 .988.68 1.669q.682.68 1.67.68t1.67-.68M6.922 20h10.173z");
}

</style>
