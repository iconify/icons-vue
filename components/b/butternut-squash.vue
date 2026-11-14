<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzrrnyk9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:butternut-squash" /></template>
<style>
.nzrrnyk9j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.137 4.566q1.176.187 1.893.904q.063.062.109.137t.074.16q.027.084.034.172t-.006.175l-.93 6.047q2.632 2.063 1.336 5.833q-1.463 4.256-7.147 4.256q-5.071 0-6.281-4.034q-1.149-3.831 1.865-5.84q.769-.513 2.376-1.021q1.25-.396 1.607-.717l1.205-4.82q.051-.201.198-.348q.793-.793 2.148-.938l.394-2.166q.027-.147.108-.272q.08-.126.203-.211t.269-.116t.292-.005t.272.108q.126.08.211.203t.116.269t.005.292z");
}

</style>
