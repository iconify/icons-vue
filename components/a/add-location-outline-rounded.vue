<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1ks3joso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-location-outline-rounded" /></template>
<style>
.v1ks3joso {
  fill: currentColor;
  d: path("M11.5 10.5V13q0 .213.144.356t.357.144t.356-.144T12.5 13v-2.5H15q.213 0 .356-.144t.144-.357t-.144-.356T15 9.5h-2.5V7q0-.213-.144-.356t-.357-.144t-.356.144T11.5 7v2.5H9q-.213 0-.356.144t-.144.357t.144.356T9 10.5zm.5 9.177q2.82-2.454 4.458-4.991t1.638-4.39q0-2.744-1.737-4.53Q14.62 3.981 12 3.981T7.641 5.766t-1.737 4.53q0 1.852 1.638 4.39T12 19.677m-.47.802q-.234-.077-.432-.25q-1.067-.981-2.164-2.185q-1.096-1.203-1.99-2.493t-1.468-2.633t-.572-2.622q0-3.173 2.066-5.234Q9.037 3 12 3t5.03 2.062q2.066 2.061 2.066 5.234q0 1.279-.572 2.613q-.572 1.333-1.458 2.632q-.885 1.3-1.981 2.494T12.92 20.21q-.193.173-.44.26t-.481.086t-.47-.077M12 10.116");
}

</style>
