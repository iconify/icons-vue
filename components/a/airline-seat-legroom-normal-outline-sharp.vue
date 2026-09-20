<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwwtidbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-legroom-normal-outline-sharp" /></template>
<style>
.hwwtidbuu {
  fill: currentColor;
  d: path("M15.942 20.423V14.5h-9.5v-11h5v7h6.347v8.23h2.769v1.693zM13.866 16.5H4.442v-13h1v12h8.424z");
}

</style>
