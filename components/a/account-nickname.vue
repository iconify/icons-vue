<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lo213ccpy"/><path class="dkp81sx_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-nickname" /></template>
<style>
.dkp81sx_j {
  d: path("M6.5 12A1.25 1.25 0 1 0 9 12a1.25 1.25 0 1 0-2.5 0m5-2.5h6m-6 4h3m.625 6.75l.061-.489a1.5 1.5 0 0 1 .428-.875l3.011-3.011a1.237 1.237 0 0 1 1.75 0a1.237 1.237 0 0 1 0 1.75l-3.011 3.011a1.5 1.5 0 0 1-.875.428l-.489.061a.784.784 0 0 1-.875-.875");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lo213ccpy {
  d: path("M12.652 18.5H8.793q-.302 0-.595-.068q-.294-.069-.565-.202t-.504-.325t-.417-.43L3.731 13.6q-.066-.085-.124-.176t-.109-.185t-.094-.193t-.077-.201q-.035-.102-.061-.206q-.026-.105-.044-.211t-.026-.213q-.009-.107-.009-.215t.009-.215t.026-.213t.044-.211q.026-.104.061-.206q.034-.102.077-.201q.043-.098.094-.193t.109-.185t.124-.176l2.981-3.875q.184-.239.417-.43q.234-.192.504-.325q.271-.133.565-.202q.293-.068.595-.068h9.582q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v4.891");
}

</style>
