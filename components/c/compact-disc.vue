<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqs2erbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:compact-disc" /></template>
<style>
.cqs2erbqz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M12 8.25q-3.75 0-3.75 3.75T12 15.75T15.75 12T12 8.25m-6.894 4.965q.702 3.98 4.499 5.363q.07.025.143.036q.073.012.147.008q.073-.003.145-.02t.139-.049q.067-.031.126-.075q.06-.044.11-.098t.088-.118t.064-.132q.025-.07.036-.143q.012-.073.008-.147q-.003-.073-.02-.145t-.049-.139t-.075-.126t-.098-.11t-.118-.088t-.132-.064q-2.984-1.086-3.535-4.213q-.013-.073-.04-.142t-.066-.131q-.04-.062-.091-.116q-.051-.053-.112-.095q-.06-.043-.128-.072q-.068-.03-.14-.046t-.146-.018t-.146.011t-.142.04t-.131.066t-.116.091q-.053.051-.095.112q-.043.06-.072.128q-.03.068-.046.14t-.018.146t.011.146");
}

</style>
