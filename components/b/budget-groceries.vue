<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7dom5ryz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:budget-groceries" /></template>
<style>
.i7dom5ryz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.25 8.25h1.272Q13.78 4.125 17 4.125q3.345 0 3.493 4.452q.401.237.717.647q.75.973.437 2.162l-.542 2.062Q20.145 13 19 13h-2q-2.071 0-3.536 1.464Q12 15.929 12 18q0 .655.147 1.25H6.349q-1.927-.001-2.417-1.864l-1.579-6q-.313-1.189.437-2.162q.409-.531.96-.772V7q0-3.5 3.5-3.5h1.5q1.45 0 2.475 1.025T12.25 7zm-7 0h5.5V7q0-.828-.586-1.414T8.75 5h-1.5q-2 0-2 2zM17 5.625q-1.764 0-1.972 2.625h3.944Q18.764 5.625 17 5.625m0 8.625q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906M17 17q-1 0-1 1t1 1t1-1t-1-1");
}

</style>
