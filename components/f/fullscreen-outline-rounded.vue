<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk0o04bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fullscreen-outline-rounded" /></template>
<style>
.uk0o04bad {
  fill: currentColor;
  d: path("M5 19h2.923q.213 0 .356.144t.144.357t-.144.356t-.356.143H4.808q-.343 0-.576-.232T4 19.192v-3.115q0-.213.144-.356t.357-.144t.356.144t.143.356zm14.02 0v-2.923q0-.213.143-.356q.144-.144.357-.144t.356.144t.143.356v3.115q0 .344-.232.576t-.575.232h-3.116q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143zM5 5v2.923q0 .213-.144.356t-.357.144t-.356-.144T4 7.923V4.808q0-.343.232-.576T4.808 4h3.115q.213 0 .356.144t.144.357t-.144.356T7.923 5zm14.02 0h-2.924q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h3.116q.343 0 .575.232t.232.576v3.115q0 .213-.144.356t-.356.144t-.356-.144t-.144-.356z");
}

</style>
