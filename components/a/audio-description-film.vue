<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb08z3xgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:audio-description-film" /></template>
<style>
.jb08z3xgc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 2.25H6q-1.76 0-3.005 1.245T1.75 6.5v5q0 1.76 1.245 3.005T6 15.75h5V14.5q0-3.5 3.5-3.5h4.75V6.5q0-1.76-1.245-3.005T15 2.25m-3.952 4.808l.064.036q1.122.623 1.122 1.906t-1.121 1.906l-.066.036q-1.109.616-2.204-.028Q7.75 10.27 7.75 9t1.094-1.914t2.204-.028M12.25 14.5q0-2.25 2.25-2.25H20q2.25 0 2.25 2.25V18q0 2.25-2.25 2.25h-2.737l-2.294 1.836q-.058.046-.124.08q-.065.034-.136.054q-.071.021-.145.027q-.073.007-.147-.002q-.073-.008-.144-.03t-.135-.058t-.121-.083t-.103-.105q-.079-.1-.122-.221q-.042-.12-.042-.248v-1.326q-1.5-.337-1.5-2.174zm1.5 0V18q0 .75.75.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v.44l1.281-1.026q.1-.079.221-.122q.12-.042.248-.042h3q.75 0 .75-.75v-3.5q0-.75-.75-.75h-5.5q-.75 0-.75.75M15 15.75V15h2.422q-1.056.75-2.422.75");
}

</style>
