<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n607ufb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-drink" /></template>
<style>
.n607ufb6s {
  fill: currentColor;
  d: path("M6.975 22q-.775 0-1.337-.513T5 20.226L3 2h18l-2 18.225q-.075.75-.638 1.263T17.026 22zM5.65 8h12.7l.4-4H5.25zm8.375 10.175q.825-.825.825-2.025q0-1.025-.663-2.225T12 11q-1.525 1.725-2.187 2.925T9.15 16.15q0 1.2.825 2.025T12 19t2.025-.825");
}

</style>
