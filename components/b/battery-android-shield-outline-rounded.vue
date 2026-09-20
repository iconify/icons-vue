<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5g93ob4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-shield-outline-rounded" /></template>
<style>
.l5g93ob4i {
  fill: currentColor;
  d: path("M4.385 17q-1 0-1.693-.692T2 14.616V9.385q0-1 .692-1.693T4.385 7h7.852q.25 0 .374.159q.125.158.125.341t-.127.341T12.21 8H4.385q-.58 0-.982.403Q3 8.806 3 9.385v5.23q0 .58.403.982q.403.403.982.403h9.811q.214 0 .357.143t.143.357t-.143.357t-.357.143zM3 16V8zm15.177.06q-.161-.04-.298-.121q-1.35-.76-2.213-2.404t-.968-3.614q-.025-.212.109-.341t.345-.16q.602-.099 1.302-.426t1.567-.902q.217-.136.479-.136t.479.136q.887.581 1.58.905t1.295.422q.192.031.32.17q.128.14.128.332q-.106 1.99-.984 3.624q-.877 1.634-2.202 2.393q-.137.081-.296.121q-.159.041-.32.041t-.323-.04m.323-.92q1.067-.536 1.827-1.873t.932-2.973q-.594-.142-1.268-.468T18.5 8.971z");
}

</style>
