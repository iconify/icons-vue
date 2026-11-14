<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="najpr2bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:canned-tomatoes" /></template>
<style>
.najpr2bsx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.5q-8.25 0-8.25 3v13q0 3.25 8.25 3.25q3.228 0 5.54-.771q2.71-.903 2.71-2.479v-13q0-1.49-2.731-2.309Q15.217 2.5 12 2.5m-6.75 16V7.513Q7.268 8.5 12 8.5q3.217 0 5.519-.691q.707-.212 1.231-.469V18.5q0 .495-1.684 1.056q-2.081.694-5.066.694t-5.066-.694Q5.25 18.995 5.25 18.5m8.41-7.153q.635.291 1.168.825Q16 13.343 16 15q0 4-4 4t-4-4q0-3.781 3.574-3.988q.726-.989 2.303-1.252q.073-.012.146-.01q.074.003.146.019q.072.017.139.047q.068.031.128.074t.111.096t.089.117t.066.132q.026.069.038.142t.01.146t-.019.146t-.047.139q-.031.068-.074.128t-.096.111t-.117.089t-.132.066q-.069.026-.142.038q-.251.042-.463.107");
}

</style>
