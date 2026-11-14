<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfc64nbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flag-off" /></template>
<style>
.yfc64nbos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.95 4h8.241q.103 0 .206.014q.102.013.202.041q.1.027.195.067t.185.093q.089.053.17.117t.153.138t.134.157q.061.083.111.174t.087.187q.038.096.062.197q.024.1.035.203t.008.206q-.003.104-.02.206t-.047.201t-.074.193q-.043.094-.098.181l-.91 1.441q-.066.104-.116.217q-.051.112-.085.231q-.034.118-.052.241q-.017.122-.017.245t.017.245q.018.123.052.241q.034.119.085.231q.05.113.116.217l.91 1.441q.055.087.098.181t.074.193q.03.099.047.201t.02.206t-.008.206t-.035.203t-.062.197q-.037.097-.087.187q-.141.257-.367.444m-7.572.357H6.75q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q5 11.836 5 11.75V8.983M5 8.9V21M3.5 3.5l17 17");
}

</style>
