<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwnrcn63y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:forklift-rounded" /></template>
<style>
.jwnrcn63y {
  fill: currentColor;
  d: path("M4.962 20.5q-1.039 0-1.77-.73T2.462 18q0-.592.26-1.112q.259-.52.74-.888v-3.692q0-.348.23-.578t.577-.23H5.75V6.808q0-.348.23-.578T6.558 6h4.213q.485 0 .898.258t.606.717l3.925 9.216q.13.311.216.632q.084.321.084.677q0 1.258-.871 2.129T13.5 20.5q-.967 0-1.743-.547T10.67 18.5H7.402q-.171.88-.86 1.44q-.688.56-1.58.56m16.077-1h-2.731q-.349 0-.578-.23t-.23-.578V5q0-.213.143-.357T18 4.5t.357.143T18.5 5v13.5h2.539q.213 0 .356.143t.144.357t-.144.357t-.356.143M6.02 19.059q.441-.442.441-1.059t-.44-1.059q-.442-.441-1.06-.441t-1.058.441T3.462 18t.441 1.059t1.059.441t1.058-.441m8.889-.15q.591-.592.591-1.409t-.591-1.409T13.5 15.5t-1.409.591q-.591.592-.591 1.409t.591 1.409t1.409.591t1.409-.591M9.675 14.5h3.86q.25 0 .49.058t.471.173l-3.148-7.365q-.077-.174-.221-.27T10.791 7H6.75v4.5z");
}

</style>
