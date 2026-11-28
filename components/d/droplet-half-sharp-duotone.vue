<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w9jogfb0o"/><path class="g9d8r3bkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplet-half-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g9d8r3bkn {
  d: path("M12 7.618C12 7.0657 12.4477 6.618 13 6.618C13.2846 6.618 13.5556 6.7393 13.7454 6.9514L16.4721 10C17.456 11.1 18 12.5241 18 14C18 17.3137 15.3137 20 12 20Z");
}

.w9jogfb0o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.9629 8.6666C19.2747 10.1334 20 12.0322 20 14C20 18.4183 16.4183 22 12 22C7.5817 22 4 18.4183 4 14C4 12.0322 4.7253 10.1334 6.0371 8.6666L12 1.9999L17.9629 8.6666Z");
}

</style>
