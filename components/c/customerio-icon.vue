<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":180};
const content = `<path class="kxapoimxw"/><path class="qcj51fjnq"/><path class="h0c0hqoax"/><path class="t313ewbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:customerio-icon" /></template>
<style>
.h0c0hqoax {
  fill: var(--svg-color--af64ff, #af64ff);
  d: path("M127.843 128.016h.147c35.13 0 65.785-23.829 74.452-57.872c2.597-10.238 10.923-18.907 21.48-18.907h32.082c-.013 70.69-57.323 127.99-128.014 127.99h-.147z");
}

.kxapoimxw {
  fill: var(--svg-color--ffcd00, #ffcd00);
  d: path("M127.843 102.423a51.21 51.21 0 1 0-51.21-51.186a51.186 51.186 0 0 0 51.21 51.186");
}

.qcj51fjnq {
  fill: var(--svg-color--00ecbb, #00ecbb);
  d: path("M128.161 128.016h-.171c-35.127-.009-65.777-23.834-74.453-57.872c-2.571-10.238-10.898-18.907-21.454-18.907H0c0 70.686 57.303 127.99 127.99 127.99h.171z");
}

.t313ewbjv {
  fill: var(--svg-color--7131ff, #7131ff);
  d: path("M218.509 141.73a127.99 127.99 0 0 1-181.013 0l36.197-36.197c30 29.98 78.618 29.98 108.618 0z");
}

</style>
