<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt4sjvbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:forward-to-inbox-outline-sharp" /></template>
<style>
.mt4sjvbaw {
  fill: currentColor;
  d: path("M12 12.116L4 6.885v10.5q0 .269.173.442t.443.173H13.5v1H3V5h18v8.5h-1V6.885zM12 11l7.692-5H4.308zm6.616 10.789l-.689-.689l2.056-2.1h-4.867v-1h4.886l-2.1-2.1l.714-.688l3.288 3.288zM4 6.884v11.789V13.5v.171V6z");
}

</style>
