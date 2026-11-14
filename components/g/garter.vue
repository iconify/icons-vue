<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cukpkacmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:garter" /></template>
<style>
.cukpkacmv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.882 9.623q1.855-1.172 4.175-1.61l-1.862-.828q-.063-.028-.12-.067t-.106-.088t-.088-.107t-.067-.12q-.028-.064-.044-.131q-.016-.068-.019-.137t.006-.138t.031-.134l1-3q.039-.115.111-.211q.072-.097.171-.166q.122-.086.268-.118q.145-.033.292-.007t.273.107t.211.202L12 7.192l2.886-4.122q.085-.122.211-.202t.273-.107t.292.007q.146.032.268.118q.099.069.171.166q.072.096.111.211l1 3q.021.066.031.134q.009.069.006.138t-.019.137t-.044.131t-.067.12t-.088.107t-.106.088t-.12.067l-1.862.828q2.32.438 4.175 1.61q3.132 1.978 3.132 4.877t-3.132 4.877Q16.152 21.25 12 21.25t-7.118-1.873Q1.75 17.399 1.75 14.5t3.132-4.877");
}

</style>
