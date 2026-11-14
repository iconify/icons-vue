<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btx3dtulz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caret-right" /></template>
<style>
.btx3dtulz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m15.826 13.649l-3.295 3.06q-1.079 1.003-2.43.414T8.75 15.06V8.94q0-1.474 1.351-2.063t2.43.415l3.295 3.059q.719.668.719 1.649t-.719 1.648z");
}

</style>
