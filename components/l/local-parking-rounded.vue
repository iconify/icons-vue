<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zand_nbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-parking-rounded" /></template>
<style>
.zand_nbse {
  fill: currentColor;
  d: path("M9 14v5q0 .402-.29.701Q8.422 20 8 20q-.402 0-.701-.299T7 19V5q0-.402.299-.701T8 4h5q2.058 0 3.529 1.471T18 9t-1.471 3.529T13 14zm0-2h4.046q1.229 0 2.115-.886q.885-.885.885-2.114t-.885-2.114Q14.275 6 13.046 6H9z");
}

</style>
