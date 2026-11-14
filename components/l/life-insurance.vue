<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbf-gbbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:life-insurance" /></template>
<style>
.tbf-gbbnf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.989 17.08q2.305 2.146 4.62 3.56q.088.054.188.082q.099.028.203.028t.203-.028t.188-.082q2.315-1.414 4.62-3.56q4.739-4.41 4.739-8.33q0-2.298-1.601-3.899T16.25 3.25q-2.621 0-4.25 1.953Q10.371 3.25 7.75 3.25q-2.298 0-3.899 1.601T2.25 8.75q0 3.92 4.739 8.33m5.248-9.292l3 1q.056.019.108.046t.099.062q.048.035.089.076q.041.042.075.089q.035.048.061.1q.027.053.045.109q.018.055.027.113t.009.117v2q0 2.808-3.471 4.196q-.135.054-.279.054t-.279-.054Q8.25 14.308 8.25 11.5v-2q0-.059.009-.117t.027-.113q.018-.056.045-.109q.026-.052.061-.1q.034-.047.075-.089t.089-.076q.047-.035.099-.062t.108-.046l3-1q.115-.038.237-.038t.237.038");
}

</style>
