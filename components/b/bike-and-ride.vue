<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lity1-b6q"/><path class="n_qc-ubgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-and-ride" /></template>
<style>
.lity1-b6q {
  d: path("M2.5 8.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm15.887 3.213q.234-.101.451-.235t.412-.297q.196-.164.365-.355q.17-.19.31-.403t.247-.444t.181-.475t.11-.497t.037-.507q0-.172-.017-.343t-.05-.34q-.034-.168-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294q-.095-.143-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T17 5t-.343.017t-.34.05q-.168.034-.333.084t-.323.115q-.159.066-.311.147t-.294.177t-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333t-.05.34q-.017.171-.017.343q0 .26.039.518q.038.258.114.507t.189.484t.258.451q.146.215.322.407t.379.356t.427.295t.466.229");
}

.n_qc-ubgy {
  d: path("M6 8.5h5.5L14.75 4L17 8.5m-5.5 0l-1.25-5.25m-1 0h3m2.5.75l-.5-1.5h2.5M15 14.5h6.5V20H15Zm0 2.75h6.5m-5 2.75l-.75 1.75M20 20l.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
