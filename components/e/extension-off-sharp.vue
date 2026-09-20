<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn07tw7xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:extension-off-sharp" /></template>
<style>
.rn07tw7xp {
  fill: currentColor;
  d: path("M19.116 16.304L7.58 4.769h1.104q.156-1.121.957-1.887q.802-.767 1.916-.767q1.108 0 1.91.767q.801.766.963 1.887h4.685v4.946q.842.258 1.363 1.012T21 12.442q0 .93-.521 1.674t-1.363 1.053zM4 20.116V15.45q1.2-.077 2.014-.916t.813-2.092q0-1.13-.823-2.005T4 9.416v-4.84l15.5 15.539zm16.533 1.844L2.04 3.467l.713-.713l18.492 18.492z");
}

</style>
