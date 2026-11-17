<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui0limbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-droplet-fill" /></template>
<style>
.ui0limbyj {
  fill: currentColor;
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107m10.351-.477a8 8 0 0 0-.556-.444a1 1 0 0 0-1.162 0a8 8 0 0 0-.556.444c-1.516 1.3-2.974 3.174-2.974 5.259a4.1 4.1 0 0 0 1.204 2.907a4.11 4.11 0 0 0 7.018-2.907c0-.815-.229-1.611-.592-2.336c-.565-1.13-1.428-2.105-2.382-2.923");
}

</style>
