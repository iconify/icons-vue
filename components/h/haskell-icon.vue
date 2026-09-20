<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":181};
const content = `<path class="mqoalub4o"/><path class="vd-za9bdm"/><path class="j7smdcbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:haskell-icon" /></template>
<style>
.j7smdcbrs {
  fill: var(--svg-color--8f4e8b, #8f4e8b);
  d: path("m205.804 127.92l-20.079-30.1H256v30.102h-50.196zm-30.118-45.145l-20.078-30.1H256v30.1z");
}

.mqoalub4o {
  fill: var(--svg-color--453a62, #453a62);
  d: path("m0 180.591l60.235-90.294L0 0h45.176l60.236 90.297l-60.236 90.294z");
}

.vd-za9bdm {
  fill: var(--svg-color--5e5086, #5e5086);
  d: path("m60.235 180.591l60.236-90.294L60.235 0h45.177l120.465 180.591h-45.171l-37.645-56.432l-37.652 56.432z");
}

</style>
