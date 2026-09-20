<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r14vfjv0o"/><path class="vveb8lb6f"/><path class="afkdrspjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-nuxt-opened" /></template>
<style>
.afkdrspjq {
  fill: var(--svg-color--00dc82, #00dc82);
  d: path("M20.376 27.816h8.863a1.6 1.6 0 0 0 1.389-.792a1.56 1.56 0 0 0 0-1.58l-5.953-10.168a1.6 1.6 0 0 0-.587-.579a1.62 1.62 0 0 0-1.603 0a1.6 1.6 0 0 0-.587.58l-1.522 2.6l-2.976-5.086a1.6 1.6 0 0 0-.587-.58a1.62 1.62 0 0 0-1.604 0a1.6 1.6 0 0 0-.587.58L7.215 25.443a1.56 1.56 0 0 0 0 1.582c.14.24.343.44.587.579s.52.212.801.212h5.564c2.204 0 3.83-.955 4.949-2.818l2.715-4.638l1.455-2.482l4.366 7.455h-5.82zm-6.3-2.485l-3.882-.001l5.82-9.94l2.904 4.97l-1.944 3.322c-.743 1.208-1.587 1.649-2.898 1.649");
}

.r14vfjv0o {
  fill: var(--svg-color--7faecc, #7faecc);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21zm0 18.7H6.6V11.8h20.8zm0-14.5h-8.2l1-2.1h7.1z");
}

.vveb8lb6f {
  fill: var(--svg-color--7faecc, #7faecc);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

</style>
