<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqhaaxbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:game-achievements-list" /></template>
<style>
.wqhaaxbnx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 4.25h1.257q.122-2 2.243-2h.75q-1.243 0-2.121.879q-.879.878-.879 2.121q0 3 3 3h2.5q3 0 3-3q0-1.243-.879-2.121q-.878-.879-2.121-.879H14q.932 0 1.591.659q.569.569.647 1.341H17.5q2.75 0 2.75 2.75v12q0 2.75-2.75 2.75h-11q-2.75 0-2.75-2.75V7q0-2.75 2.75-2.75m4.25-.5q-.621 0-1.061.439q-.439.44-.439 1.061q0 1.5 1.5 1.5h2.5q1.5 0 1.5-1.5q0-.621-.439-1.061q-.44-.439-1.061-.439zm2.583 6.758q-.409-.829-1.333-.829q-.925 0-1.333.829l-.313.633q-.175.353-.565.41l-.697.102q-.915.132-1.201 1.011t.375 1.525l.506.493q.282.276.216.664l-.119.695q-.156.911.591 1.454q.748.544 1.566.114l.625-.328q.349-.184.698 0l.625.328q.818.43 1.566-.114q.747-.543.591-1.454l-.119-.695q-.066-.388.217-.664l.505-.493q.661-.646.375-1.525t-1.2-1.011l-.698-.102q-.39-.057-.565-.41z");
}

</style>
