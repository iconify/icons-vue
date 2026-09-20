<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp3zulw-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-pen-outline-sharp" /></template>
<style>
.hp3zulw-n {
  fill: currentColor;
  d: path("m12.25 10.825l.925.925L18.6 6.325l-.925-.925zM5 19h.925l5.825-5.825l-.925-.925L5 18.075zm8.875-5.125l-3.75-3.75L14.3 5.95l-.725-.725L8.1 10.7L6.7 9.3l6.875-6.875L15.7 4.55l1.975-1.975l3.75 3.75zM6.75 21H3v-3.75l7.125-7.125l3.75 3.75z");
}

</style>
