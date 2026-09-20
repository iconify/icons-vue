<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6jse0t1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:domain-disabled-check-outline" /></template>
<style>
.s6jse0t1l {
  fill: currentColor;
  d: path("m21.77 22.646l-2.504-2.492H2.73V3.608l-1.57-1.57l.708-.707l20.608 20.608zM3.73 19.154h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm4 8h3v-3h-3zm0-4h3v-3h-3zm4 4h6.535l-3-3h-3.534zm4.872-11.442l2.973-2.973l-.546-.547l-2.421 2.422L15.394 5.4l-.546.552zm3.541-4.855q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165M21.27 18.15l-1-1v-5.073h1zm-9.538-9.538l-1-1V4.153H7.235l-1-1h5.496z");
}

</style>
