<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3r5djbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-frame-shield-outline-rounded" /></template>
<style>
.r3r5djbhr {
  fill: currentColor;
  d: path("M4.385 17q-1 0-1.693-.692T2 14.616V9.385q0-1 .692-1.693T4.385 7h8.932q.214 0 .357.143t.143.357t-.143.357t-.357.143H4.384q-.578 0-.981.403T3 9.385v5.23q0 .58.403.982q.403.403.982.403h10.11q.25 0 .362.159q.112.158.112.341t-.112.341t-.363.159zm.807-2.384q-.348 0-.577-.23q-.23-.23-.23-.578v-3.616q0-.348.23-.577q.23-.23.577-.23h6.522q.272 0 .471.189t.244.463q.113.97.338 1.878t.581 1.743q.136.348-.05.653q-.187.305-.554.305zm12.985 1.444q-.161-.04-.298-.121q-1.35-.76-2.213-2.406q-.862-1.646-.968-3.612q-.006-.211.118-.341t.336-.16q.602-.099 1.302-.426t1.567-.902q.217-.136.479-.136t.479.136q.887.581 1.58.905t1.295.422q.192.031.32.17q.128.14.128.332q-.106 1.99-.984 3.624q-.877 1.634-2.202 2.393q-.137.081-.296.121q-.159.041-.32.041t-.323-.04m.323-.92q1.067-.536 1.827-1.873t.932-2.973q-.594-.142-1.268-.468T18.5 8.971z");
}

</style>
