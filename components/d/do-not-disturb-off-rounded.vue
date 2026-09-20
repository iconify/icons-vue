<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u71bd-7-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:do-not-disturb-off-rounded" /></template>
<style>
.u71bd-7-l {
  fill: currentColor;
  d: path("M12 21q-1.864 0-3.506-.71q-1.642-.711-2.857-1.926q-1.216-1.216-1.926-2.858Q3 13.864 3 12q0-1.596.521-3.012q.521-1.417 1.456-2.584L3.094 4.52q-.146-.146-.155-.347t.155-.366t.357-.166t.357.166l16.384 16.384q.146.147.156.345t-.156.363t-.357.166q-.19 0-.356-.166l-1.883-1.877q-1.167.935-2.584 1.456Q13.596 21 12 21m-1.927-9.5H8q-.213 0-.357.143T7.5 12t.14.357t.335.143h3.098zm8.583 4.344L15.312 12.5H16q.214 0 .357-.143T16.5 12t-.14-.357t-.335-.143h-1.713L8.156 5.344q-.373-.373-.286-.882q.088-.51.547-.727q.835-.368 1.732-.551T12 3q1.864 0 3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12q0 .954-.184 1.851q-.183.897-.55 1.732q-.218.46-.725.55t-.885-.289");
}

</style>
