<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wqzu4hbrw"/><path class="w1hu9xwid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:behance-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.w1hu9xwid {
  d: path("M16 5h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m0 10a2 2 0 0 0 2 2c.255 0 .523-.033.751-.155a1.2 1.2 0 0 0 .417-.4a1 1 0 1 1 1.664 1.11C20.164 18.555 19.187 19 18 19c-2 0-3.692-1.473-3.963-3.454l-.001-.001A4 4 0 0 1 14 15v-2c0-1.066.415-2.078 1.172-2.828a4 4 0 0 1 5.656 0A3.97 3.97 0 0 1 22 13a1 1 0 0 1-1 1h-5Zm3.733-3a2 2 0 0 0-1.732-1c-.714 0-1.376.382-1.734 1Z");
}

.wqzu4hbrw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 5a4 4 0 0 1 3.064 6.572a4 4 0 0 1 1.79 4.5A4 4 0 0 1 7 19H3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1Zm0 2H4v4h2c.527 0 1.028-.204 1.402-.574l.001-.001c.579-.57.756-1.433.447-2.184A2 2 0 0 0 6 7M4 17h3c.527 0 1.028-.204 1.402-.574l.001-.001l.022-.022l.001-.001a2 2 0 0 0 0-2.804l-.001-.001A2 2 0 0 0 7 13H4Z");
}

</style>
