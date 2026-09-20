<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phi44bc7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calendar-add-on-outline" /></template>
<style>
.phi44bc7h {
  fill: currentColor;
  d: path("M17.5 21.5v-3h-3v-1h3v-3h1v3h3v1h-3v3zM5.616 19q-.691 0-1.153-.462T4 17.384V6.616q0-.691.463-1.153T5.616 5h1.769V2.77h1.077V5h5.153V2.77h1V5h1.77q.69 0 1.153.463T18 6.616v5.715q-.25-.017-.5-.017t-.5.017v-1.715H5v6.769q0 .23.192.423t.423.192h6.674q0 .25.017.5t.063.5zM5 9.615h12v-3q0-.23-.192-.423T16.384 6H5.616q-.231 0-.424.192T5 6.616zm0 0V6z");
}

</style>
