<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="n6j7f3fqk"/><path class="f-exz9b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-japan" /></template>
<style>
.f-exz9b3o {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M43.971 32.569c0 6.294-5.104 11.4-11.4 11.4c-6.292 0-11.395-5.105-11.395-11.4s5.103-11.398 11.395-11.398c6.295 0 11.4 5.103 11.4 11.398");
}

.n6j7f3fqk {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M64 43c0 6.075-3.373 11-10 11H10C3.373 54 0 49.075 0 43V21c0-6.075 3.373-11 10-11h44c6.627 0 10 4.925 10 11z");
}

</style>
