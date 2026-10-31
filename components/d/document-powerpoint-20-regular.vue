<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rr_ggr66o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-powerpoint-20-regular" /></template>
<style>
.rr_ggr66o {
  fill: currentColor;
  d: path("M8 9a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2zm2.586-7a1.5 1.5 0 0 1 1.06.44l3.914 3.914a1.5 1.5 0 0 1 .44 1.06V16a2 2 0 0 1-2 2h-3.769a3 3 0 0 0 .595-1H14a1 1 0 0 0 1-1V8h-3.5A1.5 1.5 0 0 1 10 6.5V3H6a1 1 0 0 0-1 1v4H4V4a2 2 0 0 1 2-2zM3.879 16h1.128v-1.628h.506q.925 0 1.473-.464q.552-.464.552-1.29q0-.802-.492-1.21Q6.557 11 5.62 11H3.88zm1.616-4.136q.412.001.632.206q.224.206.224.586q0 .412-.227.631t-.646.22h-.471v-1.643zM11 6.5a.5.5 0 0 0 .5.5h3.293L11 3.207z");
}

</style>
