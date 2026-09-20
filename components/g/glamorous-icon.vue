<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":228};
const content = `<path class="r-gri15er"/><path class="fzisoebmx"/><path class="e19wxjwia"/><path class="yv3j4ogqq"/><path class="ljvqdhbho"/><path class="j47t-1hiy"/><path class="qrkr4_aak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:glamorous-icon" /></template>
<style>
.e19wxjwia {
  fill: var(--svg-color--ff8080, #ff8080);
  d: path("M37.644 2.182C16.752 5.592 1.402 13.267 3.534 18.81S24 25.632 44.892 22.221s36.242-11.086 34.11-16.202C76.87.049 58.536-1.656 37.644 2.182");
}

.fzisoebmx {
  fill: var(--svg-color--da233c, #da233c);
  d: path("M36.791 2.182C14.62 6.019-1.582 13.694.123 19.662c2.132 5.97 21.745 7.675 44.343 3.838c22.171-4.264 38.8-11.938 36.668-17.907c-2.132-5.97-22.172-7.249-44.343-3.411");
}

.j47t-1hiy {
  fill: var(--svg-color--b2c1c0, #b2c1c0);
  d: path("m111.178 140.444l57.267-57.299l16.587 16.577l-57.267 57.299z");
}

.ljvqdhbho {
  fill: var(--svg-color--555b61, #555b61);
  d: path("m180.935 210.152l57.275-57.291L256 170.646l-57.275 57.29z");
}

.qrkr4_aak {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M116.218 151.403L179.53 88.09l73.563 73.563l-63.312 63.312z");
}

.r-gri15er {
  fill: var(--svg-color--da233c, #da233c);
  d: path("m80.281 4.74l85.701 85.7l-47.754 47.754L.976 20.942z");
}

.yv3j4ogqq {
  fill: var(--svg-color--e8e8e8, #e8e8e8);
  d: path("m63.46 89.857l54.87-54.87l71.754 71.753l-54.87 54.87z");
}

</style>
