<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jvce5aclm"/><path class="qmet9mpyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:box-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jvce5aclm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.4362 1.1002L22.4362 5.9479C22.781 6.115 23 6.4645 23 6.8477L23 17.1523C23 17.5355 22.781 17.885 22.4362 18.0521L12.4362 22.8998C12.3002 22.9657 12.1511 23 12 23C11.8489 23 11.6998 22.9657 11.5638 22.8998L1.5638 18.0521C1.219 17.885 1 17.5355 1 17.1523L1 6.8477C1 6.4645 1.219 6.115 1.5638 5.9479L11.5638 1.1002C11.6998 1.0343 11.8489 1 12 1C12.1511 1 12.3002 1.0343 12.4362 1.1002Z");
}

.qmet9mpyl {
  d: path("M1 7.4574L1 6.8477C1 6.4645 1.219 6.115 1.5638 5.9479L11.5638 1.1002C11.6998 1.0343 11.8489 1 12 1C12.1511 1 12.3002 1.0343 12.4362 1.1002L22.4362 5.9479C22.781 6.115 23 6.4645 23 6.8477L23 7.4574L12.458 12.8889C12.3164 12.9619 12.1593 13 12 13C11.8407 13 11.6836 12.9619 11.542 12.8889L1 7.4574Z");
}

</style>
