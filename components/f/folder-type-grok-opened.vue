<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xcshbhbvc"/><path class="rsbnrr1wc"/><path class="w5bd-eb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-grok-opened" /></template>
<style>
.rsbnrr1wc {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M31 20.5A10.5 10.5 0 1 1 20.5 10A10.5 10.5 0 0 1 31 20.5");
}

.w5bd-eb0q {
  fill: var(--svg-color--0a0a0a, #0a0a0a);
  d: path("m18.793 22.555l4.987-3.702c.244-.182.594-.111.71.17a4.14 4.14 0 0 1-.88 4.5c-1.22 1.228-2.917 1.497-4.469.884l-1.694.789c2.43 1.67 5.382 1.258 7.226-.599a5.63 5.63 0 0 0 1.493-5.285l.004.004c-.615-2.657.15-3.719 1.719-5.89L28 13.27l-2.063 2.075v-.006zm-1.028.898c-1.745-1.676-1.444-4.27.045-5.765c1.1-1.107 2.904-1.559 4.478-.895l1.691-.785a5 5 0 0 0-1.143-.627a5.59 5.59 0 0 0-6.095 1.233a5.7 5.7 0 0 0-1.226 6.13c.639 1.561-.408 2.666-1.463 3.78c-.374.396-.749.79-1.051 1.21z");
}

.xcshbhbvc {
  fill: var(--svg-color--bbb, #bbb);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

</style>
