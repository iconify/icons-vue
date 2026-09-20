<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdnm8pbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:carry-on-bag-question-outline-sharp" /></template>
<style>
.pdnm8pbtz {
  fill: currentColor;
  d: path("M9.5 19V9H8v10zm2.277 1H7V8h7V4h-1.616V3H15v9.166q-.254.103-.518.236q-.265.133-.482.29V9h-3.5v10h.966q.055.273.128.512t.183.488m8.366-5.143q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165m-2.835 5.682q.217 0 .376-.16q.158-.158.158-.375q0-.218-.158-.376q-.159-.159-.376-.159t-.376.159t-.159.376t.159.376t.376.158m-.374-1.784h.747v-.173q0-.294.15-.478t.35-.384q.35-.3.55-.613t.2-.775q0-.687-.447-1.124q-.446-.438-1.176-.438q-.537 0-1 .338t-.662.874l.685.273q.113-.3.37-.525t.607-.225q.413 0 .645.207q.232.206.232.62q0 .294-.17.491q-.169.197-.369.397q-.15.15-.293.32q-.143.169-.268.33q-.075.131-.113.29q-.037.16-.037.322zM9.5 19V9zm1 0V9z");
}

</style>
