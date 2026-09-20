<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxiz7mbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:deployed-code-alert-outline-rounded" /></template>
<style>
.nxiz7mbbb {
  fill: currentColor;
  d: path("m11.692 4.173l-6.117 3.54L12 11.428l6.425-3.713l-6.117-3.541q-.154-.096-.308-.096t-.308.096M4 15.61V8.39q0-.434.212-.803t.596-.595l6.384-3.678q.212-.125.4-.172T12 3.096t.42.046q.202.047.389.172l6.384 3.678q.384.226.596.595T20 8.39v2.955q0 .213-.144.357t-.357.143t-.356-.143t-.143-.357V8.523l-6.217 3.59q-.385.218-.811.218t-.805-.217L5 8.523v7.08q0 .155.077.29t.23.23l6.059 3.527q.112.063.18.175t.07.25q0 .289-.241.422q-.24.134-.49-.007l-6.077-3.482q-.384-.226-.596-.595T4 15.61m14 5.717q.2 0 .33-.13t.132-.331t-.131-.331t-.331-.131t-.33.13q-.132.132-.132.332t.131.33t.331.131m.273-2.039q.112-.115.112-.269V16.56q0-.164-.112-.275q-.111-.112-.273-.112t-.273.116t-.111.269v2.459q0 .164.111.275t.273.112t.273-.116m-3.109 2.297Q14 20.422 14 18.75t1.165-2.835Q16.329 14.75 18 14.75t2.836 1.165T22 18.75t-1.164 2.836T18 22.75t-2.835-1.164M12 11.955");
}

</style>
