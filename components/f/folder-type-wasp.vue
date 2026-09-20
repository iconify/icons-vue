<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x9j-gesgu"/><path class="e5viygbri"/><path class="rbtlclbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-wasp" /></template>
<style>
.e5viygbri {
  fill: var(--svg-color--f5c842, #f5c842);
  d: path("M16.68 16.75v13.54h13.55V16.75");
}

.rbtlclbqx {
  fill: var(--svg-color--111, #111);
  d: path("M18.9 21.47h4.47v1.42H18.9zm0 2.67h4.47v1.43H18.9zm6.76-4.72h-1.4v1.27h.77s.16.01.27.07s.13.1.2.18q.04.06.05.15l.01.08v1.29l.01.14l.05.24q.07.17.2.32t.31.24c.1.06.29.1.3.1v.03a1 1 0 0 0-.61.35l-.2.32l-.05.24l-.01.14v1.28l-.01.1l-.06.14c-.06.08-.07.11-.2.18l-.26.07h-.77v1.27h1.54l.22-.03a2 2 0 0 0 .5-.18q.16-.1.31-.29c.1-.1.17-.24.2-.33c.04-.18.05-.42.05-.42v-1.74l.02-.13l.05-.1q.03-.07.07-.1a.4.4 0 0 1 .18-.1l.12-.01H28v-1.34h-.48l-.12-.01q-.1-.03-.18-.1l-.07-.1l-.05-.1l-.02-.08v-1.79s0-.24-.06-.43a1 1 0 0 0-.2-.33a2 2 0 0 0-.3-.29l-.2-.1l-.3-.07z");
}

.x9j-gesgu {
  fill: var(--svg-color--f7d264, #f7d264);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
