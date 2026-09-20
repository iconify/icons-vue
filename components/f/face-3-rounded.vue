<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyn7bfp0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:face-3-rounded" /></template>
<style>
.qyn7bfp0v {
  fill: currentColor;
  d: path("M12 18q3.35 0 5.675-2.337T20 10q0-.967-.212-1.843t-.602-1.648q-.598.387-1.28.593t-1.406.206q-1.427 0-2.624-.728T12 4.592q-.66 1.26-1.866 1.988q-1.207.728-2.634.728q-.723 0-1.396-.206t-1.271-.573q-.39.79-.612 1.666T4 10q0 3.325 2.338 5.663T12 18m-2.113-6.113q.363-.362.363-.887t-.363-.888T9 9.75t-.888.363T7.75 11t.363.888t.887.362t.888-.363m6 0q.362-.362.362-.887t-.363-.888T15 9.75t-.888.363t-.362.887t.363.888t.887.362t.888-.363M3.257 21q-.702 0-1.187-.525t-.429-1.227l.842-9.202q.181-1.888.984-3.54T5.54 3.632t2.927-1.927T12 1t3.532.705t2.927 1.927t2.073 2.874t.984 3.54l.842 9.202q.055.702-.43 1.227q-.484.525-1.186.525z");
}

</style>
