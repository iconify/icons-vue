<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dk1ff_qvz"/><path class="h-xc_1paa"/><path class="peeqvj2qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-congo-kinshasa" /></template>
<style>
.dk1ff_qvz {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M10.8 10.8C2.1 19.5-.1 32.2 4.1 43L43 4.1c-10.8-4.2-23.5-2-32.2 6.7m42.4 42.4c8.7-8.7 10.9-21.4 6.7-32.2L21 59.9c10.8 4.2 23.5 2 32.2-6.7");
}

.h-xc_1paa {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M53.2 10.8c-2-2-4.1-3.6-6.4-4.9L5.9 46.8c1.3 2.3 2.9 4.5 4.9 6.4c2 2 4.1 3.6 6.4 4.9l40.9-40.9c-1.3-2.3-2.9-4.5-4.9-6.4");
}

.peeqvj2qd {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M17.2 58.1c.6.3 1.2.7 1.9 1c.6.3 1.3.6 2 .9l38.8-39c-.3-.7-.5-1.3-.9-2c-.3-.6-.6-1.2-1-1.9zM44.9 4.9c-.7-.3-1.3-.6-2-.9L4.1 43c.3.7.5 1.3.9 2c.3.6.6 1.2 1 1.9l40.8-41c-.6-.4-1.2-.7-1.9-1M18 19.2l3.7 2.8l-1.4-4.6l3.7-2.9h-4.6L18 10l-1.4 4.5H12l3.7 2.9l-1.4 4.6z");
}

</style>
