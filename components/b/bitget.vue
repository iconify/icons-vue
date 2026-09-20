<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="bifb6l6_t"><path class="sizvgacnm"/><path class="uy-nfbbpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bitget" /></template>
<style>
.bifb6l6_t {
  fill: var(--svg-color--00f0ff, #00f0ff);
}

.sizvgacnm {
  d: path("M11.121 9.46h4.283l4.381 4.555a.785.785 0 0 1 .003 1.076L14.17 21H9.757l1.334-1.357l4.898-5.092l-4.836-5.092");
}

.uy-nfbbpv {
  d: path("M12.879 14.54H8.596L4.215 9.986a.785.785 0 0 1-.003-1.076L9.83 3h4.412l-1.334 1.357L8.01 9.449l4.836 5.092");
}

</style>
