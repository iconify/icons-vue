<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jj6snob8e"/><path class="b3lkym9cd"/><ellipse class="fhb_s1bey"/><ellipse class="vof4m8nhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gramophone" /></template>
<style>
.b3lkym9cd {
  d: path("M24.245 25.12h3.56l9.82-5.954l-1.874-1.471");
}

.fhb_s1bey {
  cx: 23.235px;
  cy: 17.508px;
  rx: 3.011px;
  ry: 1.501px;
}

.jj6snob8e {
  d: path("m5.206 18.077l17.99-10.485a1.43 1.43 0 0 1 1.442 0l18.156 10.662c.441.255.706.726.706 1.236v9.289c0 .51-.275.98-.716 1.236L24.706 40.412c-.441.255-.98.255-1.422 0L5.216 30.034a1.43 1.43 0 0 1-.716-1.236v-9.475c0-.52.265-.99.706-1.246");
}

.vof4m8nhs {
  cx: 23.235px;
  cy: 17.508px;
  rx: 7.415px;
  ry: 3.698px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
