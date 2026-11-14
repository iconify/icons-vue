<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnk9zi2vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:database-replica" /></template>
<style>
.rnk9zi2vn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 1.5q-6.75 0-6.75 3v8q0 .035.003.07q.151 1.624 3.052 2.404q.072.019.145.024q.074.005.147-.004t.143-.034q.07-.023.134-.06t.12-.086t.101-.107t.077-.125t.052-.137q.039-.144.02-.292q-.02-.148-.094-.277q-.075-.13-.193-.221t-.262-.129q-1.853-.498-1.945-1.07V6.662Q5.432 7.5 9 7.5q6.75 0 6.75-3q0-1.452-2.244-2.293Q11.621 1.5 9 1.5m5.5 7.25q-6.75 0-6.75 3.25v7q0 3.25 6.75 3.25T21.25 19v-7q0-3.25-6.75-3.25M9.25 19v-4.658q1.682.908 5.25.908t5.25-.908V19q0 1.75-5.25 1.75T9.25 19");
}

</style>
