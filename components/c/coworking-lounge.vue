<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8j0_n8cb"/><path class="zqg7aqb9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coworking-lounge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8j0_n8cb {
  d: path("M12.099 19H3.5v-6.5q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026t.172-.008q.086 0 .172.008t.169.026q.085.016.167.041t.162.058q.079.033.155.074t.147.088q.072.048.138.102q.067.055.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167t.026.169Q7 12.414 7 12.5V15h5.55m4.634-3.28q.054-.109.122-.209q.069-.1.151-.19t.175-.167q.094-.078.197-.142t.214-.113t.228-.082t.237-.05q.121-.017.242-.017q.132 0 .263.02t.257.059t.245.097t.228.133t.205.165t.178.195q.082.103.147.218t.112.239");
}

.zqg7aqb9b {
  d: path("M5.25 10.75V6a2.5 2.5 0 0 1 2.5-2.5h8.5a2.5 2.5 0 0 1 2.5 2.5v4.75M5.5 19v2.5m11.25-7h2.5a1.5 1.5 0 0 1 1.5 1.5v1.25a1.5 1.5 0 0 1-1.5 1.5h-2.5a1.5 1.5 0 0 1-1.5-1.5V16a1.5 1.5 0 0 1 1.5-1.5M14 21h8");
}

</style>
