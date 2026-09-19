<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ie_freblw"/><path class="ng21f-bqi"/><path class="i_biqlhip"/><path class="irju7kbvm"/></g><g class="y9tr6bcfx"><path class="abq0a518t"/><path class="y93idsc7d"/></g><g class="y9tr6bcfx"><path class="h9-vmhiov"/><path class="l3tl6hqio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:assassin" /></template>
<style>
.abq0a518t {
  d: path("M7.643 19.947c-.506 2.032-.368 4.905.7 6.376");
}

.h9-vmhiov {
  d: path("M21.986 17.308a82 82 0 0 1 8.853-1.247c7.838-.692 10.331.942 12.373 4.183c.56.889.418 1.078-1.461 1.214c-2.591.188-6.791.43-10.187 1.559l-9.283 1.092");
}

.i_biqlhip {
  d: path("M11.46 14.756c1.743-1.378 3.196-1.59 5.173-.576c.615.315.717 1.178.846 1.93m2.871 3.074c.382.949-.907 2.414-2.878 3.273c-1.97.859-3.878.786-4.26-.162h0c-.38-.949.908-2.414 2.88-3.273s3.877-.786 4.259.162");
}

.ie_freblw {
  d: path("M22.207 24.123c.899 1.943 1.034 5.14 1.806 9.33c-2.998-3.217-8.81-1.082-12.509 1c.231-1.744.192-2.923.026-4.826");
}

.irju7kbvm {
  d: path("M19.828 16.34c.104-1.5-.449-2.242-1.215-2.385c-1.092-.205-1.437.076-1.721.416");
}

.l3tl6hqio {
  d: path("M40.89 21.516c-1.06-1.86-2.268-2.55-5.748-2.61c-3.486-.06-6.972.34-10.458.845l-1.839-2.606m3.245 3.657c-1.04.498-.979 1.507-.806 2.949");
}

.ng21f-bqi {
  d: path("M18.709 13.972c1.234-.09 1.53.363 2.007.933c2.506 3 2.002 8.963 1.158 9.918c-2.09 2.36-4.874 4.804-10.41 4.776c-1.387.347-5.038-.097-5.28-1.823c-.094-1.15 2.767-1.199 2.854-2.095c.35-3.633-.99-5.184-1.93-6.465c-.819-1.119.66-5.093 4.352-4.46c1.005.173 1.766.539 2.642 1.472");
}

.y93idsc7d {
  d: path("m7.789 26.541l-1.685.283c-1.79-1.51-2.262-4.97-.486-7.038l1.74-.231");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
