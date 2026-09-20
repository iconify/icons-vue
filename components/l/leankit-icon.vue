<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":283};
const content = `<path class="mo598tb0v"/><path class="ud7b_5_ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:leankit-icon" /></template>
<style>
.mo598tb0v {
  fill: var(--svg-color--a4a7ad, #a4a7ad);
  d: path("M243.264 54.872L138.4 2.23c-6.368-2.972-13.585-2.972-19.953 0L30.143 45.957l-14.01 7.217c6.368-2.972 13.585-2.972 19.953 0L85.758 75.25l2.547.85l119.722 62.407L87.88 201.34l-1.274.425l-50.945 26.746c-6.368 2.972-13.586 3.396-19.954 0l-2.547-1.274l104.862 52.22c6.368 2.97 13.586 2.97 19.954 0l105.287-52.644C250.905 222.992 256 215.35 256 206.859V74.826c-.425-8.491-5.095-16.133-12.736-19.954");
}

.ud7b_5_ey {
  fill: var(--svg-color--4d515d, #4d515d);
  d: path("M85.758 75.25L36.086 53.174c-6.368-2.972-13.585-3.396-19.953 0l-2.548 1.274c-.424 0-.424.424-.849.424C5.095 58.693 0 66.335 0 74.826v132.033c0 8.49 5.095 16.557 12.736 20.378l2.548 1.274c6.368 2.972 13.585 3.21 19.953.238l51.795-27.027l1.273-125.198z");
}

</style>
