<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux88ldkaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:carpenter-rounded" /></template>
<style>
.ux88ldkaz {
  fill: currentColor;
  d: path("M15.475 21.3q-.275.275-.637.425t-.763.15t-.775-.15t-.65-.425l-1.4-1.4q-.275-.275-.412-.612t-.163-.688t.088-.7t.337-.65l.15-.2L3.1 5.4L7 1.5l12.725 12.725q.275.275.425.638t.15.762t-.15.775t-.425.65zm-1.4-1.425L18.3 15.65l-1.4-1.425l-4.25 4.25z");
}

</style>
