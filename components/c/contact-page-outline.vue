<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i27c_1b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-page-outline" /></template>
<style>
.i27c_1b7m {
  fill: currentColor;
  d: path("M12 13.539q.633 0 1.066-.434t.434-1.066t-.434-1.067q-.433-.433-1.066-.433t-1.066.433t-.434 1.067t.434 1.066q.433.434 1.066.434m-3.5 3.384h7v-.152q0-.465-.248-.792t-.67-.52q-.591-.255-1.24-.396q-.65-.14-1.342-.14t-1.341.14t-1.242.396q-.42.193-.669.52q-.248.327-.248.792zM17.385 21H6.615q-.69 0-1.152-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h6.961L19 8.423v10.962q0 .69-.462 1.153T17.384 21m0-1q.231 0 .424-.192t.192-.424V8.85L13.15 4H6.616q-.231 0-.424.192T6 4.615v14.77q0 .23.192.423t.423.192zM6 20V4z");
}

</style>
