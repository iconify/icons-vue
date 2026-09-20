<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsxterbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:eject-rounded" /></template>
<style>
.vsxterbwt {
  fill: currentColor;
  d: path("M6.616 17.423h10.769q.196 0 .329.133q.132.132.132.327t-.132.33t-.33.133H6.617q-.197 0-.33-.132q-.132-.133-.132-.328t.133-.33t.329-.133m.528-4.03l4.185-6.231q.13-.195.305-.278q.174-.084.366-.084t.366.084q.175.083.305.278l4.185 6.23q.273.404.035.833t-.712.429H7.82q-.475 0-.712-.429t.035-.833");
}

</style>
