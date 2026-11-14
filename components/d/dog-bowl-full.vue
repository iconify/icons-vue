<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwka1ublw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dog-bowl-full" /></template>
<style>
.uwka1ublw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.869 11.778q-.4-.55-.951-.806q.367-2.038-1.44-3.444q-1.645-1.279-3.354-.684Q14.609 4.75 12 4.75T8.876 6.844q-1.709-.595-3.354.684q-1.807 1.406-1.44 3.444q-.551.256-.951.806q-.749 1.027-.36 2.238l1.125 3.5q.558 1.734 2.38 1.734h11.448q1.822 0 2.38-1.734l1.125-3.5q.389-1.211-.36-2.238m-3.312-3.066q1.072.834.869 2.038H5.574q-.203-1.204.869-2.038q1.286-1 2.638-.09q.061.041.129.07q.069.028.141.043t.146.015t.147-.014t.141-.042t.129-.069q.062-.041.114-.093t.094-.113q.128-.19.128-.419q0-1.75 1.75-1.75T13.75 8q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.229 0 .419-.128q1.352-.91 2.638.09");
}

</style>
