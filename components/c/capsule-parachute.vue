<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="liezah5tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:capsule-parachute" /></template>
<style>
.liezah5tj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.141 4.052Q2.25 6.498 2.25 10.5q0 .084.018.165q.019.082.055.157q.036.076.088.142q.051.066.116.118l.01.008L8.7 15.932q-1.137 1.219-2.186 4.616q-.16.52-.226.715q-.038.115-.038.237q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h10q.122 0 .237-.038q.142-.048.254-.145q.113-.098.18-.232q.067-.133.077-.282q.011-.149-.036-.29q-.066-.196-.226-.715q-1.049-3.397-2.186-4.616l6.163-4.842l.01-.008q.065-.052.116-.118t.088-.142q.036-.075.055-.157q.018-.081.018-.165q0-4.002-2.891-6.448Q16.138 1.75 12 1.75T5.141 4.052m13.691 7.198l-5.091 4h-3.482l-5.091-4z");
}

</style>
