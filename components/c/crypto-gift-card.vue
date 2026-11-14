<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2jxhgk1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crypto-gift-card" /></template>
<style>
.r2jxhgk1l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 5.513q1.508-2.198 3.607-2.074q1.323.078 1.798 1.238q.284.693.115 1.573h1.23q3 0 3 3q0 2.121-1.5 2.743V18.5q0 2.75-2.75 2.75h-11q-2.75 0-2.75-2.75v-6.643q-.331-.195-.621-.486q-.879-.878-.879-2.121t.879-2.121q.878-.879 2.121-.879h1.23q-.169-.88.115-1.573q.475-1.16 1.798-1.238Q10.492 3.315 12 5.513m1.317.737h2.662q.191-.631.038-1.005q-.118-.286-.499-.309q-1.2-.07-2.201 1.314M8.482 4.936q-.381.023-.499.309q-.153.374.038 1.005h2.662Q9.682 4.866 8.482 4.936m2.768 7.314h-6v6.25q0 1.25 1.25 1.25h4.75zm1.5 7.5h4.75q1.25 0 1.25-1.25v-6.25h-6z");
}

</style>
