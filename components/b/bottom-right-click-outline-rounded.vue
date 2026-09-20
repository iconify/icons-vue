<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgeukk52y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bottom-right-click-outline-rounded" /></template>
<style>
.zgeukk52y {
  fill: currentColor;
  d: path("M4.48 20q-.213 0-.356-.143t-.143-.357t.143-.357t.357-.143h13.904q.269 0 .442-.173t.173-.442V4.519q0-.213.143-.357t.357-.143t.357.143t.143.357v13.866q0 .67-.472 1.143q-.472.472-1.143.472zm9.454-3.934Q13.5 15.633 13.5 15t.434-1.066T15 13.5t1.066.434q.434.433.434 1.066t-.434 1.066q-.433.434-1.066.434t-1.066-.434M6.5 12q-.213 0-.357-.143T6 11.5t.143-.357T6.5 11h3.792L4.566 5.26q-.147-.146-.147-.347t.147-.348t.347-.146t.347.146L11 10.293V6.5q0-.213.143-.357T11.5 6t.357.143T12 6.5v4.692q0 .349-.23.578t-.578.23z");
}

</style>
