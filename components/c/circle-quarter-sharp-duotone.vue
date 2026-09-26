<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g9eou3b7p"/><path class="ec278zj9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-quarter-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ec278zj9z {
  d: path("M12 5L12 12L19 12C19 11.0807 18.8189 10.1705 18.4672 9.3212C18.1154 8.4719 17.5998 7.7003 16.9497 7.0503C16.2997 6.4002 15.5281 5.8846 14.6788 5.5328C13.8295 5.1811 12.9193 5 12 5Z");
}

.g9eou3b7p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1Z");
}

</style>
