<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="c-r52ubsi"/><path class="wwu3eed8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-scotland" /></template>
<style>
.c-r52ubsi {
  fill: var(--svg-color--eee, #eee);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.wwu3eed8w {
  fill: var(--svg-color--0065bd, #0065bd);
  d: path("M13 18S0 8.586 0 8.895v18.21C0 27.414 13 18 13 18m5 3S3.697 31 4.07 31h27.859C32.303 31 18 21 18 21m5-3s13 9.414 13 9.105V8.895C36 8.586 23 18 23 18m-5-3S3.697 5 4.07 5h27.859C32.303 5 18 15 18 15");
}

</style>
