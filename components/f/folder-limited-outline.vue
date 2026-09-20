<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj8if0bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-limited-outline" /></template>
<style>
.gj8if0bmp {
  fill: currentColor;
  d: path("M14.402 15.094q.983-.982.983-2.402t-.983-2.401q-.983-.983-2.402-.983t-2.402.983t-.983 2.401t.983 2.402q.983.983 2.402.983t2.402-.983m-3.821-4.448q.313-.221.665-.337t.754-.117q1.05 0 1.775.725t.725 1.775q0 .402-.116.754q-.117.352-.338.666zM12 15.192q-1.05 0-1.775-.725T9.5 12.692q0-.401.116-.753q.117-.352.338-.666l3.465 3.466q-.313.22-.665.337q-.352.116-.754.116M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.981l2 2h7.789q.69 0 1.153.463T21 8.616v8.769q0 .69-.462 1.153T19.385 19zm0-1h14.769q.269 0 .442-.173t.173-.442v-8.77q0-.269-.173-.442T19.385 8h-8.19l-2-2h-4.58q-.269 0-.442.173T4 6.616v10.769q0 .269.173.442t.443.173M4 18V6z");
}

</style>
