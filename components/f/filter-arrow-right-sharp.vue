<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zft_ytbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-arrow-right-sharp" /></template>
<style>
.zft_ytbvy {
  fill: currentColor;
  d: path("M9.73 19v-6.961L3.317 4.98H19.05l-6.415 7.058V19zm9.097-1.115l-.708-.689l1.96-1.908h-4.675v-1h4.675l-1.96-1.907l.708-.708L22 14.788zm-7.635-5.739l5.643-6.165H5.55z");
}

</style>
