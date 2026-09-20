<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmi3odlwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-drink-outline" /></template>
<style>
.kmi3odlwr {
  fill: currentColor;
  d: path("M7.475 21q-.621 0-1.078-.407t-.532-1.022L4 3h16l-1.846 16.571q-.075.616-.532 1.022q-.456.407-1.078.407zM5.727 9.385l1.139 10.077q.038.23.211.384t.404.154h9.058q.23 0 .403-.154t.212-.384l1.138-10.077zm-.135-1h12.835L18.866 4H5.116zm5.452 8.336q-.394-.394-.394-.955q0-.51.28-1.084t1.07-1.66q.79 1.086 1.07 1.66t.28 1.084q0 .561-.394.955t-.956.395t-.956-.395m2.625.714q.681-.681.681-1.67q0-.794-.48-1.696T12 11.385q-1.39 1.782-1.87 2.684t-.48 1.697q0 .988.68 1.669q.682.68 1.67.68t1.67-.68M6.495 20h11.027z");
}

</style>
