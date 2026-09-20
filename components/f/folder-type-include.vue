<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sct5u5bus"/><path class="qodg8abup"/><path class="o4urrab5o"/><path class="j0ji19b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-include" /></template>
<style>
.j0ji19b1p {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("m17.523 27.326l5.577-5.577l-5.577-5.577v3.489H10.1v4.176h7.423z");
}

.o4urrab5o {
  fill: var(--svg-color--c5c5c5, #c5c5c5);
  d: path("M27.028 10H15.281a1.316 1.316 0 0 0-1.312 1.313v18.375A1.316 1.316 0 0 0 15.281 31h14.438a1.316 1.316 0 0 0 1.313-1.312V13.642Zm.394 2.133l1.247 1.148h-1.247ZM15.281 29.688V11.313h10.828v3.281h3.609v15.094Z");
}

.qodg8abup {
  fill: var(--svg-color--gray, gray);
  d: path("M15.266 11.311v18.375h14.449v-15.1h-3.6v-3.275Zm12.146.813l.008 1.158h1.252l-1.26-1.16Z");
}

.sct5u5bus {
  fill: var(--svg-color--686868, #686868);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
