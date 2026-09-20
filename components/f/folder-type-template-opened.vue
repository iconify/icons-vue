<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b9lfsbcbi"/><path class="nfts3qtls"/><path class="dltv48bqg"/><path class="xi_gbmvgd"/><path class="y76xh3xzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-template-opened" /></template>
<style>
.b9lfsbcbi {
  fill: var(--svg-color--dbad7b, #dbad7b);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.dltv48bqg {
  fill: var(--svg-color--675f58, #675f58);
  d: path("M29.025 14.38H11.974A1.98 1.98 0 0 0 10 16.354v12.675A1.98 1.98 0 0 0 11.974 31h17.051A1.98 1.98 0 0 0 31 29.026V16.354a1.98 1.98 0 0 0-1.975-1.974");
}

.nfts3qtls {
  fill: var(--svg-color--dbad7b, #dbad7b);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.xi_gbmvgd {
  fill: var(--svg-color--ccc, #ccc);
  d: path("M29.925 29.026a.905.905 0 0 1-.9.9H11.974a.905.905 0 0 1-.9-.9V17.62h18.85v11.406Z");
}

.y76xh3xzy {
  fill: var(--svg-color--ff931e, #ff931e);
  d: path("M14.9 20.246h2.8v2.801h-2.8zm4.2 0h2.8v2.801h-2.8zm4.2 0h2.8v2.801h-2.8zm-8.4 4.2h2.8v2.8h-2.8zm4.2 0h2.8v2.8h-2.8zm4.2 0h2.8v2.8h-2.8z");
}

</style>
