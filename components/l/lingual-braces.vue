<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teh-b0bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lingual-braces" /></template>
<style>
.teh-b0bup {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.763 5.788q9.237-3.079 18.474 0q.056.019.108.046t.099.062t.089.076q.041.042.075.089q.035.048.061.1q.027.053.045.109q.018.055.027.113t.009.117V15q0 3.75-3.75 3.75q-2.073 0-3-1.146q-.927 1.146-3 1.146t-3-1.146q-.927 1.146-3 1.146q-3.75 0-3.75-3.75V6.5q0-.059.009-.117t.027-.113t.045-.109q.026-.052.061-.1q.034-.047.075-.089t.089-.076t.099-.062t.108-.046M7.912 10.5Q7.581 9.25 6 9.25q-2 0-2 2t2 2q1.581 0 1.912-1.25h2.176q.331 1.25 1.912 1.25T13.912 12h2.176q.331 1.25 1.912 1.25q2 0 2-2t-2-2q-1.581 0-1.912 1.25h-2.176Q13.581 9.25 12 9.25t-1.912 1.25z");
}

</style>
