<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0qd3bbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-off-outline-sharp" /></template>
<style>
.h0qd3bbqz {
  fill: currentColor;
  d: path("M20.62 21.89L2.955 4.228l.713-.713l17.664 17.663zM8.23 15.77v-1.54h6.157l1.538 1.54zm-3-3v-1.54h1.54v1.54zm3 0v-1.54h1.54v1.54zm9 0v-1.54h1.54v1.54zm-12-3V8.23h1.54v1.54zm9 0V8.23h1.54v1.54zm3 0V8.23h1.54v1.54zM20 17.02V7h-9.994l-1-1H21v12.025zM3 18V6h3.156l1 1H4v10h13.156l1 1zm8.237-9.77h1.532v1.534zm2.994 3h1.538v1.534zM15 12");
}

</style>
