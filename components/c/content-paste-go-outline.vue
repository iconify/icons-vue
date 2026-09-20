<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkkarzb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:content-paste-go-outline" /></template>
<style>
.vkkarzb7p {
  fill: currentColor;
  d: path("m18 20.289l-.708-.714l2.075-2.075H12.5v-1h6.867l-2.075-2.08l.708-.708L21.288 17zm2-8.578h-1V5.616q0-.231-.192-.424T18.384 5H16v2.23H8V5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192H10.5v1H5.616q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h4.636q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985h4.63q.672 0 1.144.472T20 5.616zm-7.422-6.71q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23");
}

</style>
