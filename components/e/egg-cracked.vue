<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwte4qbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:egg-cracked" /></template>
<style>
.rwte4qbtl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.469 12.249q.224.01.417-.106L8 10.875l2.114 1.268q.088.053.186.08t.2.027t.2-.027t.186-.08L13 10.875l2.114 1.268q.081.049.172.076t.185.03t.187-.016t.177-.062l3-1.5q.103-.052.186-.132t.138-.181t.077-.214q.022-.112.009-.227Q18.338 1.75 12 1.75q-6.844 0-7.249 9.719q-.007.149.045.289q.051.14.152.25t.236.172q.136.063.285.069m-.355 2.108l2.5-1.5q.088-.053.186-.08t.2-.027t.2.027t.186.08l2.114 1.268l2.114-1.268q.088-.053.186-.08t.2-.027t.2.027t.186.08l2.147 1.288l2.632-1.316q.066-.033.137-.052q.071-.02.145-.025t.147.004t.143.032t.134.06t.12.085t.101.107t.079.125q.079.158.079.335q0 3.911-2.12 6.365Q15.071 22.25 12 22.25q-2.936 0-5.093-2.157T4.75 15q0-.097.025-.191q.024-.094.072-.179t.116-.154t.151-.119");
}

</style>
