<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_gr-d3_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-heart-fill-round" /></template>
<style>
.j_gr-d3_s {
  fill: currentColor;
  d: path("m15.707 6.707l-3 3a1 1 0 0 1-1.414 0l-3-3c-.589-.589-1.007-1.362-.947-2.216c.027-.378.147-.744.351-1.063c.193-.304.448-.563.748-.76c1.079-.719 2.484-.618 3.555.057c1.071-.675 2.476-.776 3.555-.057c.3.197.555.456.748.76c.204.319.324.685.351 1.063c.06.854-.358 1.627-.947 2.216M10 21a1.002 1.002 0 0 1-1.707.707l-4.999-4.999l-.001-.001l-.001-.001l-.999-.999a.999.999 0 1 1 1.414-1.414l.293.293l2.293-2.293C7.049 11.537 7.896 11 9 11h3c.942 0 1.827.439 2.394 1.191l1.899-1.898a3.121 3.121 0 1 1 4.414 4.414l-5 5C14.992 20.422 14.039 21 13 21Zm2-4h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 0-2H9c-.524 0-.941.356-1.293.707L5.414 16l3 3H13c.468 0 .98-.395 1.293-.707l5-5a1.121 1.121 0 1 0-1.586-1.586l-2.74 2.74A3 3 0 0 1 12 17");
}

</style>
