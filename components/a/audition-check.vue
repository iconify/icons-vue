<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf_ihcccb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audition-check" /></template>
<style>
.mf_ihcccb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5h4A1.5 1.5 0 0 1 15 4v8a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8 12V4a1.5 1.5 0 0 1 1.5-1.5Zm-4.5 8q0 .16.008.319t.023.318q.016.159.039.317q.024.158.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297t.129.292t.144.285q.075.141.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209t.252.196t.261.184q.132.088.269.17t.278.157q.141.076.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055t.317.039t.318.023t.319.008q.163 0 .327-.008m4.094-1.727q.245-.228.466-.479q.221-.252.414-.525q.194-.272.358-.564q.165-.291.299-.598q.133-.306.235-.625t.17-.646t.103-.661Q18 10.835 18 10.5M11.5 17v.3m0 1.4v2.8m-3.5 0h6.3m.45-3.5l2 2L21 15.75");
}

</style>
