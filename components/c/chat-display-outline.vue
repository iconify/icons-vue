<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0rpwcchv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-display-outline" /></template>
<style>
.d0rpwcchv {
  fill: currentColor;
  d: path("M4 12.5v5.144V4zm2.5-2h11v-1h-11zm0-3h11v-1h-11zM3 20.077V4.616q0-.691.463-1.153T4.615 3h14.77q.69 0 1.152.463T21 4.616v8.203q-.239-.102-.479-.172T20 12.539V4.616q0-.231-.192-.424T19.385 4H4.615q-.23 0-.423.192T4 4.615v13.03L5.65 16h4.312q-.02.096-.02.192V17H6.077zM6.5 13.5h4.814q.486-.477 1.13-.738t1.383-.262H6.5zm7.442 7.5q-.69 0-1.152-.462t-.463-1.153V16.5q0-.69.463-1.153t1.152-.462h5.443q.69 0 1.153.462T21 16.5v2.885q0 .69-.462 1.152T19.385 21zm0-1h5.443q.269 0 .442-.173t.173-.442V16.5q0-.27-.173-.442q-.173-.174-.442-.174h-5.443q-.269 0-.442.174q-.173.173-.173.442v2.885q0 .269.173.442t.442.173");
}

</style>
