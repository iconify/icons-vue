<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syedl7bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fmd-bad-outline-rounded" /></template>
<style>
.syedl7bsf {
  fill: currentColor;
  d: path("M12.357 12.03q.143-.144.143-.357V6.981q0-.213-.144-.356t-.357-.144t-.356.144t-.143.356v4.692q0 .213.144.356t.357.144t.356-.144M12 15.135q.262 0 .439-.177q.176-.177.176-.439t-.177-.438t-.438-.177t-.438.177t-.177.438t.177.439t.438.177m0 4.542q2.82-2.454 4.458-4.991t1.638-4.39q0-2.744-1.737-4.53Q14.62 3.981 12 3.981T7.641 5.766t-1.737 4.53q0 1.852 1.638 4.39T12 19.677m-.47.802q-.234-.077-.432-.25q-1.067-.981-2.164-2.185q-1.096-1.203-1.99-2.493t-1.468-2.633t-.572-2.622q0-3.173 2.066-5.234Q9.037 3 12 3t5.03 2.062q2.066 2.061 2.066 5.234q0 1.279-.572 2.613q-.572 1.333-1.458 2.632q-.885 1.3-1.981 2.494T12.92 20.21q-.193.173-.44.26t-.481.086t-.47-.077M12 10.116");
}

</style>
