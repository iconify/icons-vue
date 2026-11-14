<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6v1bccph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anchor-add" /></template>
<style>
.z6v1bccph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 2V18m-4-8.5h8M2.5 12q0 .147.007.294q.007.148.022.294q.014.147.036.292q.022.146.05.291q.029.144.065.287t.078.284q.043.141.093.279q.049.139.106.275t.119.269t.132.263t.146.257t.157.248q.082.123.17.241q.087.119.181.232q.093.114.192.223t.203.214q.105.104.214.203t.223.192q.113.094.232.181q.118.088.241.17q.122.082.248.157q.127.076.257.146t.263.132t.269.119t.275.106q.138.05.279.093t.284.078q.143.036.287.065q.145.028.291.05q.145.022.292.036q.146.015.294.022q.147.007.294.007q.499 0 .991-.082q.492-.083.963-.245q.472-.163.91-.401t.831-.545m1.371-1.512q.227-.358.402-.745q.175-.388.294-.796q.118-.408.178-.828q.06-.421.06-.846m3.5 3v6m-3-3h6");
}

</style>
