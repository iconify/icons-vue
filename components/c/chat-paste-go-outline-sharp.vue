<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8_0lab_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-paste-go-outline-sharp" /></template>
<style>
.a8_0lab_m {
  fill: currentColor;
  d: path("m18 20.289l-.708-.689l2.075-2.1H14.5v-1h4.867l-2.075-2.1l.708-.688L21.288 17zm-14.5-.5V4.5h15v6.517q-.125-.011-.25-.014T18 11t-.25.003t-.25.014V5.5h-13v11h7.517q-.011.125-.014.25T12 17t.003.25t.014.25H5.79zM7.116 9.5h7.769v-1h-7.77zm0 4h4.769v-1h-4.77zm-2.616 3v-11z");
}

</style>
