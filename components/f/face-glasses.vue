<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdqrnru9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:face-glasses" /></template>
<style>
.qdqrnru9x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M8 7.5q-3.5 0-3.5 3.5q0 1.75.875 2.625T8 14.5q3.102 0 3.455-2.75h1.09Q12.898 14.5 16 14.5q3.5 0 3.5-3.5T16 7.5q-3.102 0-3.455 2.75h-1.09Q11.102 7.5 8 7.5m7.143 8.614q-.038-.063-.088-.118t-.109-.099t-.126-.075t-.138-.05t-.146-.021q-.073-.004-.146.007t-.143.036t-.133.063q-2.114 1.268-4.228 0q-.063-.038-.133-.063t-.143-.036t-.146-.007t-.146.021t-.138.05q-.067.031-.126.075q-.06.044-.109.099q-.05.055-.088.118t-.063.133t-.036.143t-.007.146q.003.074.021.146t.05.138t.075.126t.099.109t.118.088q2.886 1.732 5.772 0q.063-.038.118-.088t.099-.109t.075-.126q.032-.066.05-.138t.021-.146t-.007-.146t-.036-.143t-.063-.133");
}

</style>
