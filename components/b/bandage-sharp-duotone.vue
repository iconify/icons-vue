<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hgdleftdo"/><path class="uow53abuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bandage-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hgdleftdo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.7365 2.2929L21.7071 7.2635C21.8946 7.451 22 7.7053 22 7.9706C22 8.2358 21.8946 8.4901 21.7071 8.6777L8.6777 21.7071C8.4901 21.8946 8.2358 22 7.9706 22C7.7053 22 7.451 21.8946 7.2635 21.7071L2.2929 16.7365C2.1054 16.549 2 16.2947 2 16.0294C2 15.7642 2.1054 15.5099 2.2929 15.3223L15.3223 2.2929C15.5099 2.1054 15.7642 2 16.0294 2C16.2947 2 16.549 2.1054 16.7365 2.2929Z");
}

.uow53abuo {
  d: path("M18.3848 12L12 18.3848L5.6152 12L12 5.6152L18.3848 12Z");
}

</style>
