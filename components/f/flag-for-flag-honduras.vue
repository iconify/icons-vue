<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ixuz6lu9q"/><path class="m7j8yp7zv"/><path class="d-jqbc8mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-honduras" /></template>
<style>
.d-jqbc8mm {
  fill: var(--svg-color--2657a7, #2657A7);
  d: path("M18.265 17.76l-.249-.766l-.249.766h-.806l.652.473l-.249.767l.652-.474l.652.474l-.249-.767l.652-.473zm5.332 2.48l-.249.766l.652-.473l.652.473l-.249-.766l.652-.473h-.806L24 19l-.249.767h-.806zm.652-4.48L24 14.994l-.249.766h-.806l.652.473l-.249.767l.652-.474l.652.474l-.249-.767l.652-.473zm-12.707 4.48l-.249.766l.652-.473l.652.473l-.249-.766l.652-.473h-.806L11.945 19l-.249.767h-.806zm.652-4.48l-.249-.766l-.249.766h-.806l.652.473l-.249.767l.652-.474l.652.474l-.249-.767l.652-.473z");
}

.ixuz6lu9q {
  fill: var(--svg-color--eee, #EEE);
  d: path("M0 14h36v8H0z");
}

.m7j8yp7zv {
  fill: var(--svg-color--0156a3, #0156A3);
  d: path("M32 5H4a4 4 0 0 0-4 4v5h36V9a4 4 0 0 0-4-4zM0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-5H0v5z");
}

</style>
