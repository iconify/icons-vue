<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k45zyhbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:device-preview" /></template>
<style>
.k45zyhbeg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.375 1.75h5.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-5.25q-2.123 0-3.624-1.501T4.25 17.125V6.875q0-2.123 1.501-3.624T9.375 1.75M12 8.5q-2.382 0-4.607 3.059q-.034.048-.061.1t-.045.109q-.019.056-.028.115q-.009.058-.009.117t.009.117t.028.115t.045.109t.061.1Q9.618 15.5 12 15.5t4.607-3.059q.034-.048.061-.1t.045-.109t.028-.115t.009-.117t-.009-.117t-.028-.115q-.018-.056-.045-.109q-.027-.052-.061-.1Q14.382 8.5 12 8.5");
}

</style>
