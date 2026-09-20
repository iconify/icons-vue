<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":229};
const content = `<path class="khh5rmb4b"/><path class="i0y_p5b8u"/><path class="vajhq-6cr"/><path class="vcv_4mb8t"/><path class="nur4j2b6n"/><path class="jy92xwbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-drive-2020" /></template>
<style>
.i0y_p5b8u {
  fill: var(--svg-color--ea4335, #ea4335);
  d: path("M215.681 225.212c3.96-2.346 7.332-5.572 9.677-9.677l4.692-8.064l22.434-38.855a26.57 26.57 0 0 0 3.518-13.196q-27.315-3.502-40.247-3.502q-13.899 0-40.248 3.502q9.754 25.075 16.422 36.655q6.724 11.683 23.752 33.137");
}

.jy92xwbjc {
  fill: var(--svg-color--ffba00, #ffba00);
  d: path("m215.242 77.71l-37.243-64.514c-2.345-4.106-5.718-7.331-9.677-9.677l-40.32 69.792l47.358 82.109h80.496c0-4.546-1.173-9.09-3.519-13.196z");
}

.khh5rmb4b {
  fill: var(--svg-color--0066da, #0066da);
  d: path("m19.354 196.034l11.29 19.5c2.346 4.106 5.718 7.332 9.677 9.678q17.009-21.591 23.68-33.137q6.77-11.717 16.641-36.655q-26.604-3.502-40.32-3.502q-13.165 0-40.322 3.502c0 4.545 1.173 9.09 3.519 13.196z");
}

.nur4j2b6n {
  fill: var(--svg-color--00ac47, #00ac47);
  d: path("M128.001 73.311L87.681 3.52c-3.96 2.346-7.332 5.571-9.678 9.677L3.519 142.224A26.57 26.57 0 0 0 0 155.42h80.642z");
}

.vajhq-6cr {
  fill: var(--svg-color--00832d, #00832d);
  d: path("M128.001 73.311q19.68-23.768 27.125-36.655q5.996-10.377 13.196-33.137C164.363 1.173 159.818 0 155.126 0h-54.25C96.184 0 91.64 1.32 87.68 3.519q9.16 26.103 15.544 37.154q7.056 12.213 24.777 32.638");
}

.vcv_4mb8t {
  fill: var(--svg-color--2684fc, #2684fc);
  d: path("M175.36 155.42H80.642l-40.32 69.792c3.958 2.346 8.503 3.519 13.195 3.519h148.968c4.692 0 9.238-1.32 13.196-3.52z");
}

</style>
