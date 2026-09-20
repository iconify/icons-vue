<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="uypib39ja"><path class="o8zmn15jc"/><path class="gcklmmv2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lsk" /></template>
<style>
.gcklmmv2f {
  d: path("M10.115 18.18h2.547L10.343 21H8.921l-4.242-5.013L9.9 6.65l1.574 2.685l-3.53 6.308z");
}

.o8zmn15jc {
  d: path("M10.47 5.62L11.942 3l7.379 12.961L15.066 21h-3.403l4.37-5.37c-1.865-3.331-3.74-6.657-5.563-10.01");
}

.uypib39ja {
  fill: var(--svg-color--0288d1, #0288d1);
}

</style>
