<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v9z9jjbhw"/><path class="lfqtad9_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agent-mic-off" /></template>
<style>
.lfqtad9_w {
  d: path("M4 10.5q0 .16.008.319t.023.318q.016.159.039.317q.024.158.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297t.129.292t.144.285q.075.141.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209t.252.196t.261.184q.132.088.269.17t.278.157q.141.076.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055t.317.039t.318.023t.319.008q1.113 0 2.163-.37m3.949-3.919Q17 11.639 17 10.5M10.5 17v3.5m-3.5 0h7m.5-6L21 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9z9jjbhw {
  d: path("M11.543 13.5H8.5q-.074 0-.147-.007t-.146-.022q-.072-.014-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087t-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126t-.063-.133t-.049-.139t-.036-.142q-.015-.073-.022-.146T7 12V4q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T8.5 2.5h4q.074 0 .147.007t.146.022t.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139t.036.142t.022.146T14 4v7.079");
}

</style>
