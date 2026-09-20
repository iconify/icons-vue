<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdde9_bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:beenhere" /></template>
<style>
.bdde9_bvv {
  fill: currentColor;
  d: path("m12 21.77l-6.354-4.766q-.298-.218-.472-.566T5 15.713V4.616q0-.691.463-1.153T6.616 3h10.769q.69 0 1.153.463T19 4.616v11.096q0 .379-.174.727t-.472.565zm-1.05-7.462l4.958-4.958l-.708-.72l-4.25 4.25l-2.138-2.138l-.72.708z");
}

</style>
