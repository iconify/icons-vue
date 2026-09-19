<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="d2kvgvbvc"><g class="iqrupbcod"><path class="t3avwcb3g"/><path class="jplr8x1kd"/></g><path class="wt3rov7ge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:jeans" /></template>
<style>
.d2kvgvbvc {
  fill-rule: evenodd;
}

.iqrupbcod {
  fill: var(--svg-color--28316b, #28316b);
}

.jplr8x1kd {
  d: path("m15.667.511l-2.927 10.01L10 62.189s5.665 3.281 13.161 1.084a61 61 0 0 0 2.833-.889q.001-.019-.004-.035a1.8 1.8 0 0 1 .102-.839l2.37-40.714s2.924-1.264 3.84 0V.509H15.667");
}

.t3avwcb3g {
  d: path("m45.445.511l2.927 10.01l2.74 51.668s-5.665 3.281-13.161 1.084a62 62 0 0 1-2.834-.889q.002-.019.006-.035a1.76 1.76 0 0 0-.102-.839l-2.37-40.714s-2.925-1.264-3.84 0V.508h16.634");
}

.wt3rov7ge {
  fill: var(--svg-color--5e70b4, #5e70b4);
  d: path("m13.328 62.19l2.743-51.67L18.993.51h-1.737l-2.922 10.01l-2.742 51.67s3.571 2.063 8.791 1.818c-4.258-.2-7.05-1.818-7.05-1.818m34.333 0l-2.742-51.67L42 .51h1.737l2.925 10.01l2.742 51.67s-3.571 2.063-8.793 1.818c4.258-.201 7.05-1.819 7.05-1.819M33.05.511s.739 9.55-.739 11.267l-.462-.429s1.307-3.26.652-10.467z");
}

</style>
