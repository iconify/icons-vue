<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r0bubjbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-archive-32-regular" /></template>
<style>
.r0bubjbwt {
  fill: currentColor;
  d: path("M29 27.5a3 3 0 0 1-3 3h-6a3 3 0 0 1-3-3V22h12zM20.75 24a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5zM16 5c1.7 0 3.682.561 5.258 1.85c1.42 1.163 2.472 2.889 2.697 5.208c1.378.165 2.714.682 3.781 1.507c.523.403.984.885 1.352 1.435H26.31c-.915-.633-2.106-1-3.311-1a1 1 0 0 1-1-1c0-2.2-.865-3.666-2.008-4.6C18.818 7.438 17.3 7 16 7c-2.2 0-3.666.865-4.6 2.008C10.438 10.182 10 11.7 10 13a1 1 0 0 1-1 1c-3.624 0-5 2.528-5 4c0 .855.216 1.836.878 2.592C5.516 21.32 6.708 22 9 22h6.5v2H9c-2.707 0-4.516-.82-5.628-2.092C2.284 20.664 2 19.145 2 18c0-2.356 1.93-5.53 6.057-5.953c.171-1.456.74-3.016 1.794-4.305C11.166 6.135 13.2 5 16 5m13.5 11.5a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-13a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1z");
}

</style>
