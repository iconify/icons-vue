<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cin6vcc0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:defence-shield" /></template>
<style>
.cin6vcc0u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.779 4.804l-7.5-3Q12.144 1.75 12 1.75t-.279.054l-7.5 3q-.104.041-.191.112q-.088.07-.151.164q-.063.093-.096.2t-.033.22V11q0 7.214 7.915 11.171q.078.039.163.059t.172.02t.172-.02t.163-.059Q20.25 18.214 20.25 11V5.5q0-.112-.033-.22q-.033-.107-.096-.2t-.151-.164q-.087-.071-.191-.112m-6.574 3.565l.172.473q.164.451.642.491l.623.052q.89.074 1.144.929t-.451 1.403l-.354.275q-.385.3-.266.774l.143.572q.222.889-.533 1.408t-1.505-.007l-.39-.273q-.43-.3-.86 0l-.39.273q-.75.526-1.505.007t-.533-1.408l.143-.572q.119-.474-.267-.774l-.353-.275q-.705-.548-.451-1.403t1.144-.929l.623-.052q.478-.04.642-.491l.172-.473q.307-.844 1.205-.844t1.205.844");
}

</style>
