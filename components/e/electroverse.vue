<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="erxc9eb1f"/><path class="l365j6biv"/><circle class="hlcowkbbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:electroverse" /></template>
<style>
.erxc9eb1f {
  d: path("m23.49 9.81l-4.53 13.782s-.992 2.209.235 2.027c1.024-.152 4.622-.534 4.634-.536c0 0 1.644-.16 1.742.943c.101 1.148-.64 12.06-.64 12.06s.21.747.99.277c.681-.41 4.441-17.459 4.441-17.459s.225-.972-.766-.807c-1.653.276-3.066.496-3.066.496s-1.771.34-1.859-1.418c-.053-1.056-.043-9.289-.043-9.289c-.114-.168-.437-.774-1.137-.075");
}

.hlcowkbbb {
  cx: 14.057px;
  cy: 33.188px;
  r: 2.119px;
}

.l365j6biv {
  d: path("M24.686 19.337c9.222-4.612 16.946-6.732 17.748-4.78c.75 1.857-4.97 6.763-13.253 11.585a104 104 0 0 1-3.63 2.016c-.01.01-.02.01-.031.01c-3.366 1.784-6.595 3.271-9.444 4.38m3.355-10.384C10.821 27.081 4.796 32.19 5.566 34.088c.433 1.066 2.88.929 6.51-.148");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
