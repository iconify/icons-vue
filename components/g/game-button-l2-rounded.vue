<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hit-drbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-l2-rounded" /></template>
<style>
.hit-drbqq {
  fill: currentColor;
  d: path("M13.589 14.337v-.056l1.34-1.202q.806-.742 1.145-1.31t.34-1.219q0-.802-.526-1.264t-1.402-.463q-.492 0-.92.174t-.797.553q-.125.104-.106.259t.135.274q.11.119.254.111t.27-.111q.276-.23.55-.335q.272-.106.603-.106q.483 0 .777.266q.294.265.294.704q0 .501-.279.938t-1.038 1.19l-1.635 1.566q-.05.03-.111.265v.229q0 .148.124.263t.272.114h3.34q.179 0 .306-.124t.127-.303t-.127-.296t-.306-.118zm-5.43.013V9.396q0-.179-.125-.305q-.126-.125-.305-.125t-.302.125t-.123.305v4.973q0 .348.23.578t.577.23h2.581q.18 0 .296-.117q.118-.118.118-.296q0-.18-.117-.297t-.297-.117zM3 17.384V8.27q0-1.361.973-2.325q.973-.963 2.354-.963h11.346q1.38 0 2.354.963Q21 6.908 21 8.27v9.116q0 .67-.472 1.143q-.472.472-1.143.472H4.615q-.67 0-1.143-.472Q3 18.056 3 17.385");
}

</style>
