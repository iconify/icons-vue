<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf0l43q_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-2-edit" /></template>
<style>
.tf0l43q_x {
  fill: currentColor;
  d: path("M11.192 10.808V5H21v5.808zM3 19v-5.808h8.808V19zm0-8.192V5h5.808v5.808zM14.23 21v-2.21l5.334-5.307q.148-.13.305-.19t.315-.062q.172 0 .338.064q.166.065.301.194l.925.944q.129.148.19.308q.062.159.062.319t-.052.322t-.2.31L16.44 21zm5.96-4.985l.925-.956l-.924-.943l-.95.95z");
}

</style>
