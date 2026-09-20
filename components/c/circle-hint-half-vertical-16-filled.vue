<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xxymfp4ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-hint-half-vertical-16-filled" /></template>
<style>
.xxymfp4ed {
  fill: currentColor;
  d: path("M8 1q.675 0 1.315.123c.437.083.655.555.486.966c-.148.359-.542.543-.925.48a5.5 5.5 0 1 0-.018 10.862c.4-.062.809.143.94.526c.138.403-.086.845-.505.923Q8.663 15 8 15A7 7 0 1 1 8 1m5.458 10.026c.368.199.506.662.265 1.004a7 7 0 0 1-1.753 1.733c-.384.266-.896.06-1.048-.383c-.119-.348.03-.727.326-.944a5.5 5.5 0 0 0 1.154-1.142c.247-.328.695-.464 1.056-.268m.524-4.735c.405-.132.843.098.916.517a7 7 0 0 1-.031 2.551c-.093.468-.618.674-1.037.447c-.317-.171-.466-.54-.406-.895a5.5 5.5 0 0 0 .02-1.69c-.057-.4.154-.805.538-.93M10.95 2.584c.17-.415.665-.595 1.033-.34a7 7 0 0 1 1.84 1.872c.26.388.045.897-.4 1.042c-.349.113-.725-.041-.938-.34c-.34-.479-.755-.9-1.227-1.248c-.309-.228-.454-.632-.308-.986");
}

</style>
