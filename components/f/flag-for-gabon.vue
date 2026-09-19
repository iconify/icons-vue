<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v6lfl72su"/><path class="jxexpib8w"/><path class="jcg8fc5kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-gabon" /></template>
<style>
.jcg8fc5kf {
  fill: var(--svg-color--3a75c4, #3a75c4);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-4H0z");
}

.jxexpib8w {
  fill: var(--svg-color--009e60, #009e60);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v4h64v-4c0-6.075-3.373-11-10-11");
}

.v6lfl72su {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("M0 25h64v14H0z");
}

</style>
