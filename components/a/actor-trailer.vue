<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c4s3anb9a"/><path class="kt3kdvpzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:actor-trailer" /></template>
<style>
.c4s3anb9a {
  d: path("M12.815 15H5.5V7.5q0-.147.014-.294t.044-.291q.028-.145.071-.286t.099-.277q.057-.136.126-.266q.07-.13.152-.253q.081-.122.175-.236t.198-.218t.218-.198t.236-.175q.123-.082.253-.152t.266-.126t.277-.099t.286-.071q.144-.029.291-.044T8.5 4.5H17q.197 0 .392.019q.196.02.388.058q.193.038.381.095t.37.132t.355.168t.336.202q.164.109.316.234q.151.125.29.264t.264.29t.234.316q.109.163.202.336q.092.174.168.355q.075.182.132.37t.095.381t.058.388Q21 8.303 21 8.5v5.185M2.5 15h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kt3kdvpzo {
  d: path("M8 17a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2.75-9.5h.5A1.75 1.75 0 0 1 13 9.25A1.75 1.75 0 0 1 11.25 11h-.5A1.75 1.75 0 0 1 9 9.25a1.75 1.75 0 0 1 1.75-1.75m7.514 7.542l.166.335a1.5 1.5 0 0 0 1.129.821l.37.053a.574.574 0 0 1 .318.979l-.268.26a1.5 1.5 0 0 0-.431 1.328l.063.368a.574.574 0 0 1-.832.605l-.331-.174a1.5 1.5 0 0 0-1.396 0l-.331.174a.574.574 0 0 1-.832-.605l.063-.368a1.5 1.5 0 0 0-.431-1.328l-.268-.26a.574.574 0 0 1 .318-.979l.37-.053a1.5 1.5 0 0 0 1.129-.821l.166-.335a.574.574 0 0 1 1.028 0");
}

</style>
