<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgythj5hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cheese-slice" /></template>
<style>
.bgythj5hv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.459 16.019q.144.15.344.205l2.75.75q.144.039.292.02t.277-.093t.221-.192t.131-.262l.004-.015q.318-1.272 1.59-.954q.527.131.807.597q.279.466.147.993q-.018.072-.021.146q-.004.073.007.146t.036.143t.063.133t.088.118t.109.099t.126.075q.066.032.138.05l.019.004l11.25 2.5q.146.033.293.007t.273-.106t.211-.203t.118-.267q.046-.205-.022-.403l-5.5-16.25q-.047-.142-.146-.254t-.232-.178t-.282-.076t-.29.038q-.159.053-.279.169l-12.5 12q-.054.051-.096.112q-.042.06-.072.128t-.045.14t-.018.146q-.001.074.012.146q.013.073.039.142t.067.131t.091.115");
}

</style>
