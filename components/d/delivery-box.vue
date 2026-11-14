<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5hnn3b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:delivery-box" /></template>
<style>
.s5hnn3b0m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.17 2.27q-1.17-.619-2.34 0L4.08 5.844q-.335.178-.586.406q.19-.001.357.087L12 10.651l2.647-1.401l-7.248-3.837q-.065-.035-.122-.081q-.058-.047-.105-.104t-.082-.122t-.057-.135t-.029-.145q-.008-.073-.001-.147q.007-.073.028-.144t.056-.136t.081-.122q.047-.058.104-.105t.122-.082t.135-.057t.145-.029q.073-.008.147-.001q.073.007.144.028t.136.056l8.149 4.314l3.899-2.064q.167-.088.357-.087q-.251-.228-.586-.406zm3.432 7.642l-.002.001l-3.85 2.039V21.5q0 .125-.041.243q-.04.119-.117.217q.289-.077.578-.23l6.75-3.574q1.33-.705 1.33-2.21V8.054q0-.379-.084-.708q-.108.207-.315.317zM3.149 7.663l8.101 4.289V21.5q0 .125.041.243q.04.119.117.217q-.289-.077-.578-.23l-6.75-3.574q-1.33-.705-1.33-2.21V8.054q0-.38.084-.708q.108.207.315.317");
}

</style>
