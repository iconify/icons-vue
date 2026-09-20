<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uri_gtbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-open-outline-rounded" /></template>
<style>
.uri_gtbaa {
  fill: currentColor;
  d: path("M11.54 12.54q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23M7 20v-1l6.442-.654q.231-.019.395-.192q.163-.173.163-.404V6.452q0-.567-.37-.983q-.368-.415-.91-.465L7.615 4.5v-1l5.23.516q.927.103 1.54.794Q15 5.5 15 6.427v11.312q0 .609-.417 1.066t-1.027.524zm0-1h10V5.116q0-.27-.173-.443t-.442-.173h-8.77q-.269 0-.442.173T7 5.116zm-2.039 1q-.213 0-.356-.143T4.46 19.5t.144-.357T4.96 19H6V5.116q0-.672.472-1.144T7.616 3.5h8.769q.67 0 1.143.472q.472.472.472 1.144V19h1.039q.213 0 .356.143t.144.357t-.144.357t-.356.143z");
}

</style>
