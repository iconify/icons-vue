<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n30n35r8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lacrosse-ball" /></template>
<style>
.n30n35r8b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.794 13.252l-2.5-7q-.019-.051-.029-.105q-.446-2.23 1.16-3.434Q7.708 1.75 10 1.75h4.5q2.61 0 3.844 1.605q1.264 1.643.352 3.924q-.036.092-.096.171l-4.5 6q-.052.07-.119.126t-.146.095t-.163.059t-.172.02h-1.318l3.497 7.431q.031.066.049.138t.021.146t-.007.146q-.011.074-.036.143q-.025.07-.063.133q-.039.063-.088.118q-.05.054-.109.098q-.06.044-.127.076q-.066.031-.138.049t-.146.021q-.073.004-.146-.007q-.074-.011-.143-.036q-.07-.025-.133-.063q-.063-.039-.118-.088q-.054-.05-.098-.109q-.044-.06-.076-.127l-3.797-8.069H8.5q-.116 0-.227-.035q-.11-.035-.205-.102t-.165-.159t-.109-.202M9.25 7.25Q9.25 10 12 10t2.75-2.75T12 4.5T9.25 7.25");
}

</style>
