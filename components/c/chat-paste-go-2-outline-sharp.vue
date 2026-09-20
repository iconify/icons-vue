<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm6vw6b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-paste-go-2-outline-sharp" /></template>
<style>
.wm6vw6b5m {
  fill: currentColor;
  d: path("m18 20.289l-.708-.689l2.075-2.1H14.5v-1h4.867l-2.075-2.1l.708-.688L21.288 17zm-14.5-.5V4.5h15v6.517q-.125-.011-.25-.014T18 11t-.25.003t-.25.014V5.5h-13v11h7.517q-.011.125-.014.25T12 17t.003.25t.014.25H5.79zm1-3.289v-11z");
}

</style>
