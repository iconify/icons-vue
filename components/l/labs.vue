<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jok71vbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:labs" /></template>
<style>
.jok71vbro {
  fill: currentColor;
  d: path("M12 21q-1.804 0-3.075-1.241T7.654 16.73V7.654q-.69 0-1.172-.472Q6 6.709 6 6.019V4.654q0-.682.486-1.168T7.654 3h8.673q.69 0 1.182.486q.491.486.491 1.168v1.365q0 .69-.492 1.163q-.491.472-1.181.472v9.365q-.115 1.69-1.366 2.836T12 21m2.357-1.942q.97-.943.97-2.327v-.75h-3.193v-1h3.193v-2.846h-3.193v-1h3.193V7.654H8.654v9.077q0 1.384.98 2.327q.982.942 2.367.942t2.356-.942");
}

</style>
