<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj2nqy1qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:forklift-sharp" /></template>
<style>
.xj2nqy1qy {
  fill: currentColor;
  d: path("M4.962 20.5q-1.039 0-1.77-.73T2.462 18q0-.592.26-1.112q.259-.52.74-.888v-4.5H5.75V6h6.096L16.2 16.19q.13.312.216.633q.084.321.084.677q0 1.258-.871 2.129T13.5 20.5q-.967 0-1.743-.547T10.67 18.5H7.402q-.171.88-.86 1.44q-.688.56-1.58.56m12.538-1v-15h1v14h3.039v1zm-11.48-.441q.441-.442.441-1.059t-.44-1.059q-.442-.441-1.06-.441t-1.058.441T3.462 18t.441 1.059t1.059.441t1.058-.441m8.889-.15q.591-.592.591-1.409t-.591-1.409T13.5 15.5t-1.409.591q-.591.592-.591 1.409t.591 1.409t1.409.591t1.409-.591M9.675 14.5h3.86q.25 0 .49.058t.471.173L11.194 7H6.75v4.5z");
}

</style>
