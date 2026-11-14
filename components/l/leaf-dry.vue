<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3rgw7b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-dry" /></template>
<style>
.a3rgw7b7u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.838 14.917l.294 2.937q.043.433.179.774l8.159-8.158q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-8.158 8.159q.341.136.774.179l3 .3q1.168.117 1.932-.774l.584-.681q.204-.238.516-.26l1.876-.134q1.499-.107 1.975-1.532l.446-1.338q.118-.356.474-.475l1.262-.42q1.539-.513 1.539-2.135V10.5q0-.25.15-.45l.753-1.004q.67-.894.363-1.968l-.566-1.983q-.343-1.202-1.545-1.545l-1.983-.566q-1.074-.307-1.968.363L13.95 4.1q-.2.15-.45.15h-1.919q-1.622 0-2.134 1.539l-.422 1.262q-.118.356-.474.475l-1.262.42q-1.539.513-1.539 2.135v1.669q0 .375-.3.6l-.723.542q-1.016.761-.889 2.025");
}

</style>
