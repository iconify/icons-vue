<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="actfvpzax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:goalkeeper-dive" /></template>
<style>
.actfvpzax {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 6.501v-.002q-.001-1.346.951-2.298q.952-.953 2.299-.953t2.299.953t.951 2.298q.001 1.347-.951 2.3T18 9.752q-1.216 0-2.11-.777l-5.451 3.634l-3.944 3.067l2.141 3.427q.079.126.104.273t-.009.293q-.034.145-.12.266q-.087.122-.214.201q-.062.039-.131.065t-.142.039t-.147.01t-.146-.019t-.139-.047t-.127-.073q-.061-.043-.111-.097t-.09-.117L5.5 16.915l-1.864 2.982q-.039.063-.09.117t-.111.097t-.127.073t-.139.047q-.072.016-.146.019t-.147-.01q-.073-.012-.142-.039q-.069-.026-.131-.065q-.127-.079-.214-.201q-.086-.121-.12-.266q-.033-.146-.009-.293q.025-.147.104-.273l2.5-4q.071-.113.176-.195l4.5-3.5q.021-.017.044-.032l5.412-3.608q-.246-.583-.246-1.267M7.25 5.5q-2.5 0-2.5 2.5t2.5 2.5q1.036 0 1.768-.732T9.75 8t-.732-1.768T7.25 5.5");
}

</style>
