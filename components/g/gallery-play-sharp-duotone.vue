<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qnlhdibuj"/><path class="rw7tfuxmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-play-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qnlhdibuj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 6C21.552 6 22 6.45 22 7V21C22 21.55 21.552 22 21 22H3C2.448 22 2 21.55 2 21V7C2 6.45 2.448 6 3 6H21ZM20 2V4H4V2H20Z");
}

.rw7tfuxmm {
  d: path("M9.033 9.5C9.36 9.33 9.757 9.35 10.062 9.56L15.376 13.17C15.649 13.36 15.813 13.67 15.813 14C15.813 14.33 15.649 14.64 15.376 14.83L10.062 18.44C9.757 18.65 9.36 18.67 9.033 18.5C8.748 18.35 8.545 18 8.5 17.69V10.38C8.5 10.01 8.706 9.67 9.033 9.5Z");
}

</style>
