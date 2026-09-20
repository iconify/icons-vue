<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyhuhqbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-agenda-clock-24-filled" /></template>
<style>
.cyhuhqbzf {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m.25-9A3.25 3.25 0 0 1 21 6.25v5.774A6.47 6.47 0 0 0 17.5 11a6.5 6.5 0 0 0-1.783.25H7.75l-.102.007a.75.75 0 0 0 0 1.486l.102.007h5.315a6.5 6.5 0 0 0-1.75 2.75H7.75l-.102.007a.75.75 0 0 0 0 1.486L7.75 17h3.27q-.019.248-.02.5c0 1.29.377 2.49 1.024 3.5H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zm-.25 11a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5H20a.5.5 0 0 0 0-1h-2v-2.5a.5.5 0 0 0-.5-.5M7.648 7.007a.75.75 0 0 0 0 1.486l.102.007h8.5l.102-.007a.75.75 0 0 0 0-1.486L16.25 7h-8.5z");
}

</style>
