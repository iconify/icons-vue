<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8f1_3bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:location-off-rounded" /></template>
<style>
.v8f1_3bkz {
  fill: currentColor;
  d: path("M11.53 20.479q-.234-.077-.432-.25q-1.067-.987-2.164-2.188q-1.095-1.2-1.99-2.49t-1.468-2.629t-.572-2.622q0-.9.192-1.712T5.63 7.05L2.22 3.642q-.146-.146-.146-.337t.146-.357t.357-.165t.376.165l18.515 18.516q.146.146.156.347t-.156.366t-.357.165t-.356-.165l-4.985-4.985q-.605.708-1.307 1.459q-.702.75-1.543 1.559q-.198.173-.442.26t-.479.086t-.47-.077M12 3q2.964 0 5.03 2.062t2.066 5.234q0 .76-.211 1.592q-.212.831-.654 1.735q-.217.454-.705.526q-.487.072-.855-.295l-3.165-3.165q.067-.143.088-.281t.022-.292q0-.349-.131-.634t-.348-.503t-.503-.348T12 8.5q-.154 0-.292.021q-.139.021-.281.088L8.356 5.54q-.373-.373-.33-.87q.043-.498.472-.765q.76-.443 1.644-.673Q11.027 3 12 3");
}

</style>
