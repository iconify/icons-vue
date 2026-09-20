<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g57q-19dl"/><path class="ai-xc8nxt"/><path class="xzcmotq0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eti" /></template>
<style>
.ai-xc8nxt {
  fill: var(--svg-color--333, #333);
  d: path("M11.804 3v5.612h-4.04v7.28h3.537V21A9.01 9.01 0 0 1 3 12.016C3 7.103 6.923 3.106 11.804 3");
}

.ft5dv1b6b {
  fill: none;
}

.g57q-19dl {
  fill: var(--svg-color--31aaa7, #31aaa7);
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.xzcmotq0y {
  fill: var(--svg-color--eef1f8, #eef1f8);
  d: path("M10.942 3.016v4.749H8.295c-.254 0-.53.196-.53.45v1.138h7.571c.482 0 .9-.244.9-.725c0-.482-.418-.863-.9-.863H12.53v-4.75zM7.765 11.47v4.658c0 .25.212.636.477.636h2.7V21h1.588v-4.235h2.822c.487 0 .884-.318.884-.773c0-.46-.397-.816-.884-.816H9.687c-.227 0-.333-.211-.333-.423v-1.297c0-.212.106-.397.328-.397h5.643c.503 0 .91-.25.91-.725c0-.477-.407-.863-.91-.863z");
}

</style>
