<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gotgup8ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-drink-sharp" /></template>
<style>
.gotgup8ix {
  fill: currentColor;
  d: path("M6.027 21L4 3h16l-2.008 18zM5.592 8.385h12.835L18.866 4H5.116zm8.077 9.05q.681-.681.681-1.67q0-.794-.48-1.696T12 11.385q-1.39 1.782-1.87 2.684t-.48 1.697q0 .988.68 1.669q.682.68 1.67.68t1.67-.68");
}

</style>
