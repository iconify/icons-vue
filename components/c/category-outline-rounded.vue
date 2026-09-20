<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taf09sdvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:category-outline-rounded" /></template>
<style>
.taf09sdvq {
  fill: currentColor;
  d: path("m8.637 8.994l2.667-4.402q.13-.211.308-.295q.177-.084.388-.084t.389.084t.307.295l2.668 4.402q.13.202.13.424t-.105.409t-.285.295t-.417.109H9.314q-.239 0-.418-.109q-.179-.108-.284-.29t-.106-.404t.13-.434M17.5 21.231q-1.567 0-2.649-1.082T13.769 17.5t1.082-2.649t2.649-1.082t2.649 1.082t1.082 2.649t-1.082 2.649t-2.649 1.082M3.77 19.922v-4.85q0-.343.231-.573q.233-.23.576-.23h4.85q.344 0 .574.232q.23.233.23.577v4.85q0 .343-.233.573q-.232.23-.576.23h-4.85q-.343 0-.573-.233q-.23-.232-.23-.576m13.73.309q1.147 0 1.94-.792t.792-1.939t-.792-1.939t-1.939-.792t-1.939.792t-.792 1.939t.792 1.939t1.938.792m-12.73-.5h4.462v-4.462H4.769zm4.858-10.5h4.746L12 5.427zM17.5 17.5");
}

</style>
