<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="us5whwbyu"/><path class="zuhekjblt"/><path class="sxtcdr_iw"/><path class="hixg29ivq"/><path class="e7adu8ier"/><path class="mr-hmtq-m"/><path class="xdb0v3y6p"/><path class="wxskpnb6f"/></g><path class="n1ae2clug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:central" /></template>
<style>
.e7adu8ier {
  d: path("M30.159 33.976v5.621c0 1.608-1.157 2.903-2.594 2.903s-2.594-1.295-2.594-2.903l-.019-6.335c4.405-.37 7.93-3.891 8.31-8.312");
}

.hixg29ivq {
  d: path("M14.318 17.84h-5.72c-1.608 0-2.903 1.156-2.903 2.593s1.295 2.594 2.903 2.594l6.142.011m18.943 7.124l7.225 7.225c1.137 1.137 1.234 2.87.218 3.887s-2.75.918-3.887-.219l-7.08-7.08");
}

.mr-hmtq-m {
  d: path("M33.683 30.16h5.719c1.608 0 2.903-1.156 2.903-2.593s-1.295-2.594-2.903-2.594l-6.142-.011m-18.942 5.2l-7.226 7.225c-1.137 1.137-1.234 2.87-.218 3.887s2.75.918 3.887-.219l7.08-7.08");
}

.n1ae2clug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.658 22.019A5.997 5.997 0 0 0 18 24a5.997 5.997 0 0 0 11.658 1.981");
}

.sxtcdr_iw {
  d: path("M17.841 14.024V8.403c0-1.608 1.157-2.903 2.594-2.903s2.594 1.295 2.594 2.903l.019 6.335c-4.405.37-7.93 3.891-8.31 8.312");
}

.us5whwbyu {
  d: path("m33.683 17.838l7.225-7.225c1.137-1.137 1.234-2.87.218-3.887s-2.75-.918-3.887.219l-7.08 7.08");
}

.wxskpnb6f {
  d: path("M14.318 30.16h-5.72c-1.608 0-2.903-1.156-2.903-2.593s1.295-2.594 2.903-2.594l6.142-.011");
}

.xdb0v3y6p {
  d: path("M17.841 33.976v5.621c0 1.608 1.157 2.903 2.594 2.903s2.594-1.295 2.594-2.903l.019-6.335c-4.405-.37-7.93-3.891-8.31-8.312");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zuhekjblt {
  d: path("M30.159 14.024V8.403c0-1.608-1.157-2.903-2.594-2.903S24.97 6.795 24.97 8.403l-.019 6.335c4.405.37 7.93 3.891 8.31 8.312m.422-5.21h5.719c1.608 0 2.903 1.156 2.903 2.593s-1.295 2.591-2.903 2.594l-6.142.011m-18.942-5.2l-7.226-7.225c-1.137-1.137-1.234-2.87-.218-3.887s2.75-.918 3.887.219l7.08 7.08");
}

</style>
