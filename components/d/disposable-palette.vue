<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0m721byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:disposable-palette" /></template>
<style>
.v0m721byt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.799 5.769Q1.75 8.337 1.75 12t3.049 6.231Q7.791 20.75 12 20.75q1.328 0 2.535-.251q-.057.003-.114-.003q-.073-.008-.144-.03t-.135-.057t-.122-.082q-.056-.048-.103-.105q-.046-.058-.081-.123q-.034-.065-.055-.136t-.028-.144t.001-.148q.565-5.367 7.184-5.918q.073-.007.147.002q.073.008.143.031q.071.022.135.058t.121.083t.103.106t.08.123q.034.066.054.137t.026.145q.007.073-.002.147q-.008.073-.031.143q-.022.071-.058.135t-.083.121q-.048.057-.106.103t-.123.08q-.066.034-.137.054t-.145.026q-5.381.449-5.816 4.582q-.016.148-.087.279t-.187.225q-.086.07-.189.112q2.467-.572 4.418-2.214Q22.25 15.663 22.25 12t-3.049-6.231Q16.209 3.25 12 3.25T4.799 5.769M10 8.25q0-2 2-2t2 2t-2 2t-2-2M7 8.5q2 0 2 2t-2 2t-2-2t2-2m10 0q2 0 2 2t-2 2t-2-2t2-2m-9.5 6.75q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5");
}

</style>
