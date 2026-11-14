<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qi01urbau"/><path class="j1cphlbua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:actor-trailer" /></template>
<style>
.j1cphlbua {
  d: path("M9 7.5h4V11H9Zm8.75 6.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.qi01urbau {
  d: path("M9.015 15H5.5V7.5q0-.147.014-.294t.044-.291q.028-.145.071-.286t.099-.277q.057-.136.126-.266q.07-.13.152-.253q.081-.122.175-.236t.198-.218t.218-.198t.236-.175q.123-.082.253-.152t.266-.126t.277-.099t.286-.071q.144-.029.291-.044T8.5 4.5H17q.197 0 .392.019q.196.02.388.058q.193.038.381.095t.37.132t.355.168t.336.202q.164.109.316.234q.151.125.29.264t.264.29t.234.316q.109.163.202.336q.092.174.168.355q.075.182.132.37t.095.381t.058.388Q21 8.303 21 8.5v5.085M2.5 15h3m3.652.189q-.128.06-.247.137t-.225.172q-.107.093-.199.201t-.169.228t-.134.249q-.059.129-.098.265t-.06.277Q8 16.858 8 17q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T10 19q.146 0 .29-.021q.145-.021.285-.063t.272-.104t.254-.142q.122-.081.231-.178t.202-.209t.17-.236t.134-.259");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
