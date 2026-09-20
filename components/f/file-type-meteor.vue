<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t6ona68-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-meteor" /></template>
<style>
.t6ona68-h {
  fill: var(--svg-color--df4f4f, #df4f4f);
  d: path("m2 2.273l23.979 25.4a1.12 1.12 0 0 0 1.442-.1a1.064 1.064 0 0 0 .144-1.344zm7.593 2.401l18.26 19.686a1.12 1.12 0 0 0 1.442-.1a1.064 1.064 0 0 0 .144-1.344zM4.259 9.811L22.519 29.5a1.12 1.12 0 0 0 1.442-.1a1.064 1.064 0 0 0 .144-1.344zm11.752-3.073l12.758 13.754a.78.78 0 0 0 1.007-.067a.74.74 0 0 0 .1-.939zm-9.995 9.027l12.757 13.753a.78.78 0 0 0 1.007-.067a.74.74 0 0 0 .1-.939zm16.551-6.05l5.782 6.252a.4.4 0 0 0 .5-.031a.335.335 0 0 0 .05-.44l-6.33-5.781ZM9.208 22.1l5.782 6.252a.4.4 0 0 0 .5-.031a.335.335 0 0 0 .05-.44z");
}

</style>
