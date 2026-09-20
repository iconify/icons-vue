<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbwz-3b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lightbulb-circle-rounded" /></template>
<style>
.pbwz-3b-d {
  fill: currentColor;
  d: path("M12.726 18.216q.313-.245.409-.639h-2.27q.097.394.409.64q.313.245.726.245t.726-.246M9.75 16.192h4.5q.192 0 .317-.125t.125-.316t-.125-.317t-.317-.126h-4.5q-.192 0-.317.125t-.125.316t.125.317t.317.126m-.629-2.269h5.758q.828-.628 1.32-1.593q.493-.964.493-2.1q0-1.946-1.372-3.319T12 5.539T8.68 6.91t-1.372 3.32q0 1.135.492 2.1q.493.964 1.321 1.592m.338-.884q-.589-.571-.928-1.298t-.339-1.515q0-1.576 1.115-2.69T12 6.424t2.693 1.114q1.115 1.113 1.115 2.689q0 .788-.34 1.515t-.928 1.298zM12.004 21q-1.866 0-3.51-.708q-1.643-.709-2.859-1.924T3.71 15.512T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709");
}

</style>
