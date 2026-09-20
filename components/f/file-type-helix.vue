<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h737-shnb"/><path class="xnmj5d7un"/><path class="v2too5ejm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-helix" /></template>
<style>
.h737-shnb {
  fill: var(--svg-color--00aeef, #00aeef);
  d: path("M19.5 17.479h-7a1.479 1.479 0 1 1 0-2.958h7a1.479 1.479 0 0 1 0 2.958");
}

.v2too5ejm {
  fill: var(--svg-color--00aeef, #00aeef);
  d: path("M5.9 15.7c0 .789-.592 5.028 6.507 8.972a15 15 0 0 1 2.169-2.169c-.1-.1-1.282-.789-1.38-.887C8.754 19.352 8.853 16.2 8.853 15.9v-.3c0-.3.2-2.662 4.338-5.028c5.324-3.155 6.31-5.817 6.408-6.31l-2.958-.789v-.1a4.8 4.8 0 0 1-1.183 1.577l-4.83-2.75a1.9 1.9 0 0 0-.789-.2a1.42 1.42 0 0 0-1.282.789a1.5 1.5 0 0 0 .592 2.07l3.845 2.169a5.6 5.6 0 0 1-1.282.789c-5.62 3.352-5.912 7-5.812 7.883");
}

.xnmj5d7un {
  fill: var(--svg-color--00aeef, #00aeef);
  d: path("M26.106 16.3c0-.789.592-5.028-6.507-8.972a15 15 0 0 1-2.169 2.165c.1.1 1.282.789 1.38.887c4.437 2.268 4.338 5.423 4.338 5.718v.3c0 .3-.2 2.662-4.338 5.028c-5.324 3.155-6.31 5.817-6.408 6.31l2.958.789v.1a4.8 4.8 0 0 1 1.183-1.577l4.831 2.752a1.9 1.9 0 0 0 .789.2a1.42 1.42 0 0 0 1.282-.789a1.5 1.5 0 0 0-.592-2.07l-3.845-2.169a5.6 5.6 0 0 1 1.282-.789c5.521-3.352 5.816-7 5.816-7.883");
}

</style>
