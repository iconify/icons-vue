<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmjz144ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:do-the-dishes" /></template>
<style>
.qmjz144ia {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.386 4.386Q1.75 7.022 1.75 10.75t2.636 6.364t6.364 2.636q1.206 0 2.297-.276Q13 19.122 13 18.75q0-2.078 3.586-5.664q.139-.14.303-.249t.346-.185q.182-.075.375-.114q.193-.038.39-.038t.39.038t.375.114t.346.185t.303.249l.04.04q.296-1.127.296-2.376q0-3.728-2.636-6.364T10.75 1.75T4.386 4.386M5.75 10.75q0-2.071 1.464-3.536Q8.679 5.75 10.75 5.75t3.536 1.464t1.464 3.536t-1.464 3.536q-1.465 1.464-3.536 1.464t-3.536-1.464T5.75 10.75m8.5 8q0-1.561 3.22-4.78q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q3.22 3.219 3.22 4.78q0 3.75-3.75 3.75t-3.75-3.75m1.5 0q0-.845 2.25-3.18q2.25 2.335 2.25 3.18Q20.25 21 18 21t-2.25-2.25");
}

</style>
