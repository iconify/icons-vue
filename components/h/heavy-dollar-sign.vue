<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u_wawzxqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:heavy-dollar-sign" /></template>
<style>
.u_wawzxqb {
  fill: var(--svg-color--4d5357, #4d5357);
  d: path("M48.9 28.2H15.1c-3.1 0-5.6-2.5-5.6-5.6S12 17 15.1 17h33.8c3.1 0 5.6 2.5 5.6 5.6H62c0-7.2-5.9-13.1-13.1-13.1H35.8V2h-7.5v7.5H15.1C7.9 9.5 2 15.4 2 22.6s5.9 13.1 13.1 13.1h33.8c3.1 0 5.6 2.5 5.6 5.6s-2.5 5.6-5.6 5.6H15.1c-3.1 0-5.6-2.5-5.6-5.6H2c0 7.2 5.9 13.1 13.1 13.1h13.1V62h7.5v-7.5h13.1c7.2 0 13.1-5.9 13.1-13.1s-5.8-13.2-13-13.2");
}

</style>
