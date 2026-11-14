<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vero4_bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:basketball-shot-arc" /></template>
<style>
.vero4_bzn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.791q-7.356 0-9.711 6.969q-.023.07-.033.143q-.009.073-.004.147t.024.145t.052.138t.078.124q.045.059.1.108q.056.048.12.085t.134.061q.141.047.29.037t.283-.076t.232-.178t.146-.254Q5.721 5.291 12 5.291t8.289 5.949q.048.141.146.254q.099.112.232.178q.134.066.283.076t.29-.037q.07-.024.134-.061t.12-.085q.055-.049.1-.108t.078-.124q.033-.067.052-.138t.024-.145t-.004-.147t-.033-.143Q19.356 3.791 12 3.791M5.25 15q0-2.73 1.885-4.68q.038-.054.085-.1q.046-.047.1-.085Q9.27 8.25 12 8.25t4.68 1.885q.054.038.1.085q.047.046.085.1Q18.75 12.27 18.75 15t-1.885 4.68q-.038.054-.085.1q-.046.047-.1.085Q14.73 21.75 12 21.75t-4.68-1.885q-.054-.038-.1-.085q-.047-.046-.085-.1Q5.25 17.73 5.25 15");
}

</style>
