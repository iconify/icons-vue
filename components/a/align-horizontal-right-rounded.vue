<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpaxmob4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-horizontal-right-rounded" /></template>
<style>
.tpaxmob4f {
  fill: currentColor;
  d: path("M19.374 20.857q-.143-.143-.143-.357v-17q0-.213.143-.357T19.731 3t.356.143t.144.357v17q0 .214-.144.357t-.356.143t-.357-.143m-8.585-4.55q-.414 0-.717-.302q-.303-.303-.303-.717t.303-.716t.717-.303h4.846q.413 0 .716.303t.303.716t-.303.717q-.303.303-.716.303zm-6-6.576q-.414 0-.717-.303t-.303-.717t.303-.716t.717-.303h10.846q.413 0 .716.303t.303.716t-.303.717t-.716.303z");
}

</style>
