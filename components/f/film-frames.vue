<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ntuvzxd1m"/><path class="znbkj-gsh"/><path class="kjb2y418m"/><path class="lz-6emb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:film-frames" /></template>
<style>
.kjb2y418m {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M31 7h2v3h-2zm-4 0h2v3h-2zm-4 0h2v3h-2zm-4 0h2v3h-2zm-4 0h2v3h-2zm-4 0h2v3h-2zM7 7h2v3H7zM3 7h2v3H3zm28 19h2v3h-2zm-4 0h2v3h-2zm-4 0h2v3h-2zm-4 0h2v3h-2zm-4 0h2v3h-2zm-4 0h2v3h-2zm-4 0h2v3H7zm-4 0h2v3H3z");
}

.lz-6emb5e {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("M29 25V11h1v14zM9 25V11h1v14z");
}

.ntuvzxd1m {
  fill: var(--svg-color--bbddf5, #bbddf5);
  d: path("M29 11h6v14h-6zM1 11h6v14H1zm8 0h18v14H9z");
}

.znbkj-gsh {
  fill: var(--svg-color--231f20, #231f20);
  d: path("M35 11V6H1v5h6v14H1v5h34v-5h-6V11zm-8 14H9V11h18z");
}

</style>
