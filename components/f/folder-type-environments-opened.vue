<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="d6i55kbcx"/><path class="q2tqu4q7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-environments-opened" /></template>
<style>
.d6i55kbcx {
  fill: var(--svg-color--055d7f, #055d7f);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21zm-7.2 2.1h7.1v2.1h-8.1zm5.5 6.1H6.6v-1.9h20.8v7.63z");
}

.ft5dv1b6b {
  fill: none;
}

.q2tqu4q7e {
  fill: var(--svg-color--99b8c4, #99b8c4);
  d: path("m26 26.9l.62-.61c2.86.1 2.9 0 3.03-.3l.8-1.92l.05-.18l-.07-.16c-.03-.08-.13-.33-1.92-2.04v-.9c2.06-1.99 2.02-2.09 1.9-2.38l-.78-1.94c-.12-.29-.16-.4-3.01-.32L26 15.5q.1-1.43-.1-2.83l-.08-.18l-2.04-.9c-.3-.13-.41-.18-2.34 1.92l-.87-.01c-2-2.12-2.08-2.08-2.38-1.96l-1.9.77c-.3.12-.4.16-.3 3.05l-.6.61c-2.87-.1-2.91 0-3.04.3l-.79 1.92l-.06.18l.06.16c.04.09.14.33 1.93 2.04v.9c-2.06 1.98-2.02 2.09-1.9 2.38l.78 1.94c.12.3.17.4 3 .32l.63.65q-.1 1.41.1 2.82l.07.18l2.06.9c.3.13.4.17 2.33-1.93l.87.02c2 2.12 2.1 2.08 2.39 1.96l1.9-.76c.3-.12.4-.17.28-3.06m-8.16-4.49a3.41 3.41 0 1 1 4.46 1.95a3.45 3.45 0 0 1-4.46-1.95");
}

</style>
