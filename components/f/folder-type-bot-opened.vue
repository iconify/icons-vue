<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="l7h3qub1g"><path class="x8-cdebks"/><path class="zqiamkq6d"/></g><path class="nhrwbdbgn"/><path class="q-bzkdkoq"/><path class="d7umjkwky"/><path class="f8i3edczu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-bot-opened" /></template>
<style>
.d7umjkwky {
  fill: var(--svg-color--727176, #727176);
  d: path("M14.3 16.3h1.5v3.2h-1.5zm8-4.7h1.6v1.8h-1.6zm7.7 4.7h1.5v3.2H30zm-9 9.3h3.4v1.9H21z");
}

.f8i3edczu {
  fill: var(--svg-color--aeadb3, #aeadb3);
  d: path("M14.6 11h.4v5.6h-.4zm16.2 0h.4v5.6h-.4z");
}

.l7h3qub1g {
  fill: var(--svg-color--6a004c, #6a004c);
}

.nhrwbdbgn {
  fill: var(--svg-color--aeadb3, #aeadb3);
  d: path("M15.9 13.4H30v12.2H15.9z");
}

.q-bzkdkoq {
  fill: var(--svg-color--444242, #444242);
  d: path("M24.1 16.3h3.3v2.2h-3.3zm-5.8 0h3.3v2.2h-3.3zm.2 4.5h8.9v1.9h-8.9z");
}

.x8-cdebks {
  d: path("M27.6 5.5h-9.2l-2.1 4.2H4.5v16.8h25.2v-21zm0 18.7H6.8V11.8h20.8zm0-14.5h-8.2l1-2.1h7.1z");
}

.zqiamkq6d {
  d: path("M25.9 13.7H.7l3.8 12.8h25.2z");
}

</style>
