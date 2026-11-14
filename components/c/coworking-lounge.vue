<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="deijsbctc"/><path class="ve46lgb1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coworking-lounge" /></template>
<style>
.deijsbctc {
  d: path("M11.199 19H3.5v-6.5q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147t.102-.138t.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026t.172-.008q.086 0 .172.008t.169.026q.085.016.167.041t.162.058q.079.033.155.074t.147.088q.072.048.138.102q.067.055.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167t.026.169Q7 12.414 7 12.5V15h5.45m4.734-3.28q.054-.109.122-.209q.069-.1.151-.19t.175-.167q.094-.078.197-.142t.214-.113t.228-.082t.237-.05q.121-.017.242-.017q.118 0 .235.016t.23.047q.114.031.222.078q.109.046.21.106q.101.061.194.134q.092.074.173.159q.082.085.151.181q.07.095.126.199");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ve46lgb1i {
  d: path("M5.25 10.75V6a2.5 2.5 0 0 1 2.5-2.5h8.5a2.5 2.5 0 0 1 2.5 2.5v4.75M5.5 19v2.5m9.75-7h5.5v4.25h-5.5ZM14 21h8");
}

</style>
