<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk7njnbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:deployed-code-alert-sharp" /></template>
<style>
.lk7njnbqm {
  fill: currentColor;
  d: path("M12 11.427L5.575 7.714l-.556.298v.511L12 12.573l7-4.05v-.512l-.575-.297zm-8 5.121V7.452l8-4.598l8 4.598v5.242q-.483-.171-.976-.25T18 12.365q-2.65 0-4.517 1.868t-1.867 4.517q0 .483.067.95t.22.914l.193.594zm14 4.779q.2 0 .33-.13t.132-.332t-.131-.33t-.331-.131t-.33.13q-.132.132-.132.332t.131.33t.331.131m-.385-1.923h.77v-3.231h-.77zm-2.45 2.181Q14 20.422 14 18.75t1.165-2.835T18 14.75t2.836 1.165T22 18.75t-1.164 2.836T18 22.75t-2.835-1.164");
}

</style>
