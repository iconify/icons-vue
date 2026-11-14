<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fyy5kcb1p"/><path class="sj8goc30s"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carbon-dating" /></template>
<style>
.fyy5kcb1p {
  d: path("M13.039 17.549L10.5 19l-7-4V7l7-4l7 4v4.938");
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.sj8goc30s {
  d: path("M13.862 11.973Q14 11.496 14 11q0-.172-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294t-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T10.5 7.5t-.343.017t-.34.05t-.333.084t-.323.115q-.159.066-.311.147t-.294.177t-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333q-.033.169-.05.34T7 11t.017.343t.05.34q.034.168.084.333t.115.323q.066.159.147.311t.177.294t.204.276q.11.133.231.255q.122.121.255.231q.133.109.276.204q.142.096.294.177t.311.147q.158.065.323.115t.333.084q.169.033.34.05t.343.017q.299 0 .593-.051q.295-.05.577-.15t.542-.246t.493-.335M15.5 14.75h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
