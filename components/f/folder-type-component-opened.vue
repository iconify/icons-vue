<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="anjyxdugs"/><path class="i3zgx96tq"/><g transform="matrix(.75 0 0 .75 8.5 8.5)"><g id="SVGIpSdSdWV"><path class="gzi9nsqzu"/><path class="x9vu8-b_f"/></g></g><use x="-7" y="5.6" href="#SVGIpSdSdWV" transform="matrix(.75 0 0 .75 8.5 8.5)"/><use x="7" y="5.6" href="#SVGIpSdSdWV" transform="matrix(.75 0 0 .75 8.5 8.5)"/><use y="11.2" href="#SVGIpSdSdWV" transform="matrix(.75 0 0 .75 8.5 8.5)"/><path class="ik3suihjc"/><path class="jcyix3bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-component-opened" /></template>
<style>
.anjyxdugs {
  fill: var(--svg-color--dcb67a, #dcb67a);
  d: path("M29.5 5.5H18.2l-2.1 4.2H4.3v16.8h25.2zm-2.1 18.7H6.6V11.8h20.8zm0-14.5h-8.2l1-2.1h7.1zm-1.7 4H.5l3.8 12.8h25.2z");
}

.gzi9nsqzu {
  fill: var(--svg-color--f39c12, #f39c12);
  d: path("M18.2 8.9a3.5 3.5 0 0 0 1.2-.93a2.2 2.2 0 0 0 .5-1.3V5.1a2 2 0 0 1-.35.84a3 3 0 0 1-.93.93a5 5 0 0 1-2.6.73v1.81a5 5 0 0 0 2.17-.48");
}

.i3zgx96tq {
  fill: var(--svg-color--f1c40f, #f1c40f);
  d: path("m31 17.67l-2.43-1.95l-.08-.14a2.25 2.25 0 0 0-.65-.73a3 3 0 0 0-.97-.48l-1.12-.91l-2.4-1.9c-.08-.08-.08-.15-.11-.19a2.25 2.25 0 0 0-.65-.73a3.5 3.5 0 0 0-1.97-.64h-.23a3.53 3.53 0 0 0-1.98.63a2.2 2.2 0 0 0-.63.71l-.09.18l-.14.12l-2.3 1.82l-1.12.91a3 3 0 0 0-.96.47a2.2 2.2 0 0 0-.64.7l-.08.17L10 17.66l5.25 4.21l5.25 4.2l5.25-4.2z");
}

.ik3suihjc {
  fill: var(--svg-color--f39c12, #f39c12);
  d: path("M20.5 26.05V31L31 22.6v-4.93z");
}

.jcyix3bma {
  fill: var(--svg-color--e67e22, #e67e22);
  d: path("M15.25 21.87v-.01L10 17.66v4.95l5.25 4.2l5.25 4.2v-4.95z");
}

.x9vu8-b_f {
  fill: var(--svg-color--e67e22, #e67e22);
  d: path("M13.9 8.98a5 5 0 0 0 2.1.44V7.6a5 5 0 0 1-2.67-.76a3 3 0 0 1-1.1-1.36q-.07-.17-.1-.4c-.04.51-.01 1-.02 1.48a2 2 0 0 0 .28 1.12a3.3 3.3 0 0 0 1.5 1.3");
}

</style>
