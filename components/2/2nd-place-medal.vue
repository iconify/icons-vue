<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="qocsenbwf"/><path class="v1m5d0fzf"/><path class="ixvf75yji"/><path class="v91a9nr6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:2nd-place-medal" /></template>
<style>
.ixvf75yji {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M23.205 16.026c.08-.217.131-.448.131-.693a2 2 0 0 0-2-2h-6.667a2 2 0 0 0-2 2c0 .245.05.476.131.693c-3.258 1.826-5.464 5.307-5.464 9.307C7.335 31.224 12.111 36 18.002 36s10.667-4.776 10.667-10.667c0-4-2.206-7.481-5.464-9.307");
}

.qocsenbwf {
  fill: var(--svg-color--55acee, #55acee);
  d: path("m18 8l-7-8H0l14 17l11.521-4.75z");
}

.v1m5d0fzf {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("m25 0l-7 8l5.39 7.312l1.227-1.489L36 0z");
}

.v91a9nr6n {
  fill: var(--svg-color--627077, #627077);
  d: path("M22.002 28.921h-3.543c.878-1.234 2.412-3.234 3.01-4.301c.449-.879.729-1.439.729-2.43c0-2.076-1.57-3.777-4.244-3.777c-2.225 0-3.74 1.832-3.74 1.832c-.131.15-.112.374.019.487l1.141 1.159a.36.36 0 0 0 .523 0c.355-.393 1.047-.935 1.813-.935c1.047 0 1.646.635 1.646 1.346c0 .523-.243 1.047-.486 1.421c-1.104 1.682-3.871 5.441-4.955 6.862v.374c0 .188.149.355.355.355h7.732a.37.37 0 0 0 .355-.355v-1.682a.367.367 0 0 0-.355-.356");
}

</style>
