<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3-3ruble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-color-fill-outline-rounded" /></template>
<style>
.p3-3ruble {
  fill: currentColor;
  d: path("m7.666 2.22l7.759 7.759q.479.479.479 1.156t-.479 1.155l-3.904 3.943q-.46.46-1.136.46q-.677 0-1.137-.46L5.344 12.29q-.479-.48-.479-1.156q0-.677.48-1.156L9.69 5.665L6.933 2.908q-.146-.146-.143-.335q.002-.188.149-.354q.146-.16.353-.162q.208-.003.374.162m2.738 4.16l-4.39 4.352q-.097.096-.125.202q-.03.106-.03.22h9.05q0-.114-.028-.22t-.125-.202zm7.107 10.88q-.434-.434-.434-1.067q0-.448.236-.884t.495-.827q.186-.262.378-.51q.193-.248.391-.51q.198.262.39.51q.193.248.38.51q.259.39.494.827q.236.436.236.884q0 .633-.434 1.067q-.433.433-1.066.433t-1.066-.433M3 24q-.402 0-.701-.29Q2 23.422 2 23q0-.402.299-.701T3 22h18q.402 0 .701.29q.299.289.299.71q0 .402-.299.701T21 24z");
}

</style>
