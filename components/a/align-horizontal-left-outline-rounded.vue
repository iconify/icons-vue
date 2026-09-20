<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g99gg9b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-horizontal-left-outline-rounded" /></template>
<style>
.g99gg9b0y {
  fill: currentColor;
  d: path("M4.27 21q-.214 0-.357-.143t-.144-.357v-17q0-.213.144-.357T4.269 3t.357.143t.143.357v17q0 .214-.143.357T4.269 21m4.097-4.692q-.414 0-.717-.303t-.303-.717t.303-.716t.717-.303h4.846q.413 0 .716.303t.303.716t-.303.717q-.303.303-.716.303zm0-6.577q-.414 0-.717-.303t-.303-.717t.303-.716t.717-.303h10.846q.413 0 .716.303t.303.716t-.303.717t-.716.303z");
}

</style>
