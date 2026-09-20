<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9g8yp8ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-off-sharp" /></template>
<style>
.s9g8yp8ww {
  fill: currentColor;
  d: path("M20.62 21.89L2.955 4.228l.713-.713l17.664 17.663zM8.23 15.77h7.695l-1.538-1.54H8.23zm-3-3h1.54v-1.54H5.23zm3 0h1.54v-1.54H8.23zm9 0h1.54v-1.54h-1.54zm-12-3h1.54V8.23H5.23zm9 0h1.54V8.23h-1.54zm3 0h1.54V8.23h-1.54zM3 18V6h3.156l12 12zm18 .025l-5.23-5.261V11.23h-1.56l-1.44-1.466V8.23h-1.552L9.006 6H21z");
}

</style>
