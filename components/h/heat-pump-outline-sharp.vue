<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx45gpjml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:heat-pump-outline-sharp" /></template>
<style>
.vx45gpjml {
  fill: currentColor;
  d: path("M8.26 15.74Q6.73 14.213 6.73 12t1.53-3.75Q9.789 6.712 12 6.712t3.75 1.538T17.289 12t-1.539 3.74T12 17.27t-3.74-1.53m3.298.512V13.05l-2.25 2.25q.484.398 1.049.647q.564.25 1.2.305m.885 0q.612-.056 1.189-.295t1.061-.638l-2.25-2.25zm2.877-1.56q.398-.484.638-1.061t.295-1.189h-3.183zm-2.25-3.134h3.183q-.056-.612-.295-1.189t-.638-1.061zm-.627-.608l2.25-2.25q-.484-.398-1.049-.647q-.564-.25-1.2-.305zm.04 1.532q.191-.191.191-.482t-.191-.482t-.482-.191t-.482.191t-.191.482t.191.482t.482.191t.482-.191m-.924-1.551V7.748q-.612.056-1.189.295t-1.061.638zm-3.81.627h3.183l-2.25-2.25q-.398.484-.638 1.061t-.295 1.189m.933 3.134l2.25-2.25H7.729q.075.612.324 1.189t.628 1.061M4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
