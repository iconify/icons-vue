<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3pwdq82f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:escalator-warning-outline-sharp" /></template>
<style>
.g3pwdq82f {
  fill: currentColor;
  d: path("M5.088 5.413Q4.5 4.825 4.5 4t.588-1.412T6.5 2t1.413.588T8.5 4t-.587 1.413T6.5 6t-1.412-.587M17 11q-.625 0-1.062-.437T15.5 9.5t.438-1.062T17 8t1.063.438T18.5 9.5t-.437 1.063T17 11M4.5 22v-7H3V7h6.15l4.15 7.175L14.75 12H20v5h-1v5h-4v-7.1l-.775 1.1h-2.2L9.5 11.6V22z");
}

</style>
