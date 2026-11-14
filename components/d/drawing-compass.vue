<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el01ycb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drawing-compass" /></template>
<style>
.el01ycb9q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2Q9.5 2 9.5 4.5q0 2.093 1.753 2.434q-.003.033-.003.066v1.836l-3.049 6.653q-.083.089-.133.199q-.05.109-.063.229l-2.187 4.771q-.062.135-.067.284t.046.289t.153.249q.102.11.238.172q.067.031.139.048q.071.017.145.019q.074.003.147-.008q.073-.012.142-.038t.132-.064q.063-.039.117-.089q.054-.051.098-.111q.043-.059.074-.127l2.091-4.562h5.454l2.091 4.562q.031.068.074.127q.044.06.098.111q.054.05.117.089t.132.064t.142.038q.073.011.147.008t.145-.019q.072-.017.139-.048t.127-.074t.111-.098q.05-.054.089-.117t.064-.132t.038-.142q.011-.073.008-.147t-.019-.145q-.017-.072-.048-.139l-2.187-4.771q-.013-.12-.063-.229t-.133-.199L12.75 8.836V7q0-.053-.007-.106q.571-.172 1.025-.626q.732-.732.732-1.768t-.732-1.768T12 2m2.04 13.25H9.96L12 10.8z");
}

</style>
