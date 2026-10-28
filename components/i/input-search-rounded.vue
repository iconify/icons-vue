<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_avftb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:input-search-rounded" /></template>
<style>
.b_avftb0f {
  fill: currentColor;
  d: path("M14.366 3q1.578 0 2.683 1.091q1.105 1.092 1.105 2.678q0 .648-.197 1.236q-.198.587-.56 1.074l2.834 2.848q.146.16.146.351t-.146.357q-.16.16-.364.16t-.363-.16l-2.815-2.848q-.502.37-1.088.57t-1.235.2q-1.58 0-2.684-1.104t-1.105-2.684q0-1.586 1.105-2.678T14.366 3m.004 1q-1.17 0-1.981.804t-.812 1.967t.808 1.975t1.976.812q1.17 0 1.981-.808t.812-1.977t-.808-1.971T14.37 4m3.996 15H5.616q-.687 0-1.151-.47Q4 18.06 4 17.365v-5.25q0-.69.464-1.152q.465-.463 1.151-.463h3.851q.838 1.12 2.122 1.78t2.778.662q.46 0 .91-.065q.449-.065.886-.215L20 16.572v.794q0 .694-.472 1.164t-1.162.47");
}

</style>
