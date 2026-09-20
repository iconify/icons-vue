<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ebscu7luy"/><path class="g1-lp7b4d"/><path class="xn6saabwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-storybook" /></template>
<style>
.ebscu7luy {
  fill: var(--svg-color--fff, #fff);
  d: path("m20.735 5.442l.133-3.173l2.72-.168l.122 3.23a.22.22 0 0 1-.047.143a.21.21 0 0 1-.3.029l-1.05-.82l-1.243.934a.21.21 0 0 1-.3-.04a.2.2 0 0 1-.035-.135");
}

.g1-lp7b4d {
  fill: var(--svg-color--ff4785, #ff4785);
  d: path("m20.868 2.268l-.133 3.174a.2.2 0 0 0 .043.135a.21.21 0 0 0 .3.04l1.243-.934l1.05.82a.21.21 0 0 0 .3-.029a.22.22 0 0 0 .047-.143l-.13-3.231l1.566-.1a1.415 1.415 0 0 1 1.506 1.321v25.271A1.414 1.414 0 0 1 25.245 30h-.066l-18.948-.844A1.414 1.414 0 0 1 4.876 27.8L4 4.69a1.41 1.41 0 0 1 1.33-1.458l15.537-.963Z");
}

.xn6saabwy {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.253 12.554c0 .547 3.72.285 4.22-.1c0-3.73-2.018-5.69-5.714-5.69s-5.766 1.99-5.766 4.976c0 5.2 7.077 5.3 7.077 8.136a1.127 1.127 0 0 1-1.258 1.27c-1.127 0-1.573-.572-1.52-2.512c0-.421-4.3-.553-4.43 0c-.334 4.7 2.621 6.06 6 6.06c3.276 0 5.845-1.733 5.845-4.868c0-5.573-7.182-5.423-7.182-8.185a1.18 1.18 0 0 1 1.337-1.269c.526 0 1.47.092 1.391 2.182");
}

</style>
