<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6gmxcchx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:eyeglasses-3-rounded" /></template>
<style>
.v6gmxcchx {
  fill: currentColor;
  d: path("M6.789 15.808q-1.587 0-2.698-1.111T2.981 12t1.11-2.697t2.698-1.11q1.342 0 2.346.788t1.336 2.027q.345-.139.72-.208q.376-.07.784-.07t.796.08t.758.217q.313-1.239 1.327-2.036q1.013-.799 2.356-.799q1.586 0 2.697 1.111T21.019 12t-1.11 2.697q-1.111 1.11-2.698 1.11q-1.575 0-2.692-1.098q-1.117-1.1-1.135-2.669q-.326-.157-.673-.233q-.346-.076-.736-.076q-.371 0-.705.078q-.334.08-.655.231q-.017 1.57-1.134 2.669q-1.118 1.099-2.693 1.099m-1.986-5.795q-.821.821-.821 1.987t.821 1.986t1.986.822q1.166 0 1.996-.822q.831-.82.831-1.986t-.83-1.987t-1.997-.82q-1.165 0-1.986.82m10.414 0q-.832.821-.832 1.987t.831 1.986q.831.822 1.996.822t1.987-.822t.821-1.986t-.821-1.987t-1.987-.82t-1.996.82");
}

</style>
