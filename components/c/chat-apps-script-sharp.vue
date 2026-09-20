<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y21jpgb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-apps-script-sharp" /></template>
<style>
.y21jpgb_i {
  fill: currentColor;
  d: path("M14.45 19.5q-.213 0-.357-.143T13.95 19t.143-.357t.357-.143h4.402l-3.588-2.529q-.177-.115-.211-.31t.076-.372t.308-.211t.375.076l3.632 2.523l-1.532-4.15q-.073-.183.025-.375q.097-.192.286-.265t.39.024t.275.287l1.489 4.112l1.154-4.225q.067-.189.231-.305q.165-.117.353-.05q.189.068.315.232t.058.353L20.816 19.5zm-7.334-11h7.769v-1h-7.77zm0 4h4.769v-1h-4.77zM3.5 18.788V3.5h15v6.517q-.192-.011-.385-.014q-.192-.003-.384-.003q-2.39 0-4.06 1.673Q12 13.346 12 15.731q0 .192.003.385q.003.192.014.384H5.79z");
}

</style>
