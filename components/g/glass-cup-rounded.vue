<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9u7810ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:glass-cup-rounded" /></template>
<style>
.l9u7810ed {
  fill: currentColor;
  d: path("M7.475 21q-.621 0-1.087-.404q-.467-.404-.522-1.025L4.14 4.283q-.068-.52.29-.901T5.308 3h13.384q.52 0 .877.382t.29.9l-1.705 15.29q-.056.62-.522 1.024T16.544 21zm-.938-4.5h10.952L18.866 4H5.116z");
}

</style>
