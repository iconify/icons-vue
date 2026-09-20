<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvehu7-ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:interactive-space-outline-sharp" /></template>
<style>
.nvehu7-ec {
  fill: currentColor;
  d: path("m7 8.48l1.635-1.614L7 5.25L5.384 6.866zm-4 5.29v-11h18v11h-4.686q.046-.25.061-.5t.004-.5H20v-9H4v9h3.621q-.012.25.004.5t.062.5zm13.498-6.5q.415 0 .709-.292t.293-.706t-.291-.71t-.707-.293t-.709.291t-.293.707t.291.709t.707.293M6 21.231v-1.408q0-.586.324-1.096t.874-.75q1.148-.517 2.348-.786T12 16.923t2.454.268t2.348.786q.55.24.874.745q.324.506.324 1.095v1.414zm1-1h10v-.408q0-.3-.175-.55t-.45-.375q-1.05-.475-2.15-.725T12 17.923t-2.225.25t-2.15.725q-.275.125-.45.375t-.175.55zm3.227-5.42q-.727-.726-.727-1.773t.727-1.773T12 10.538t1.773.727t.727 1.773t-.727 1.773t-1.773.727t-1.773-.727m2.836-.71q.437-.438.437-1.063t-.437-1.062T12 11.538t-1.062.438t-.438 1.062t.438 1.063t1.062.437t1.063-.437M12 20.231");
}

</style>
