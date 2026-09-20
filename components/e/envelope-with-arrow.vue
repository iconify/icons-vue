<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vtdn8bclm"/><path class="fx-r0kudv"/><path class="hlxs4oteq"/><path class="d6ywxwbyb"/><path class="nmmi1e5yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:envelope-with-arrow" /></template>
<style>
.d6ywxwbyb {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M32 10H4a3.99 3.99 0 0 0-3.595 2.275l14.766 14.767a4 4 0 0 0 5.657 0l14.767-14.767A3.99 3.99 0 0 0 32 10");
}

.fx-r0kudv {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M11.95 22.636L.637 33.949c-.027.028-.037.063-.06.091c.34.57.814 1.043 1.384 1.384c.029-.023.063-.033.09-.06L13.365 24.05a1 1 0 0 0-1.415-1.414M35.423 34.04c-.021-.028-.033-.063-.06-.09L24.051 22.636a1 1 0 1 0-1.415 1.414l11.313 11.314c.026.026.062.037.09.06a4 4 0 0 0 1.384-1.384");
}

.hlxs4oteq {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M32 10H4a4 4 0 0 0-4 4v1.03l14.528 14.496a4.88 4.88 0 0 0 6.884 0L36 15.009V14a4 4 0 0 0-4-4");
}

.nmmi1e5yi {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M26.716 7H22V2a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v5H9.148c-1.223 0-1.515.624-.651 1.489l7.863 7.863a2.23 2.23 0 0 0 3.145 0l7.863-7.863C28.232 7.624 27.94 7 26.716 7");
}

.vtdn8bclm {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V14a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
