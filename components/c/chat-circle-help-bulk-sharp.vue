<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aec7lkj0a"/><path class="op-6jbh7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-help-bulk-sharp" /></template>
<style>
.aec7lkj0a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.196 21.981a1 1 0 0 1-1.177-1.177l.935-4.673A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.op-6jbh7c {
  d: path("M9.236 9.832A3 3 0 1 1 12 14a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 11 11a1 1 0 0 1-2 0a3 3 0 0 1 .236-1.168M12.01 15a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
