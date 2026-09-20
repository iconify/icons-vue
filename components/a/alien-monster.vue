<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ab39lr_6o"/><path class="z9t7_xbju"/><radialGradient id="SVGTAPbjsgT" cx="64.344" cy="9.403" r="83.056" gradientUnits="userSpaceOnUse"><stop offset=".508" class="ibbi6dl4m"/><stop offset=".684" class="y13upsbyp"/><stop offset=".878" class="dmfxm5bje"/><stop offset=".981" class="wqx1tjbaj"/></radialGradient><path fill="url(#SVGTAPbjsgT)" class="ssqyoqd7n"/><radialGradient id="SVGCFSm0bXb" cx="63.118" cy="24.114" r="65.281" gradientUnits="userSpaceOnUse"><stop offset=".508" class="ibbi6dl4m"/><stop offset=".684" class="y13upsbyp"/><stop offset=".878" class="dmfxm5bje"/><stop offset=".981" class="wqx1tjbaj"/></radialGradient><path fill="url(#SVGCFSm0bXb)" class="y9j5_d_2r"/><radialGradient id="SVGOoDJfdBX" cx="62.811" cy="13.081" r="75.09" gradientUnits="userSpaceOnUse"><stop offset=".508" class="ibbi6dl4m"/><stop offset=".684" class="y13upsbyp"/><stop offset=".878" class="dmfxm5bje"/><stop offset=".981" class="wqx1tjbaj"/></radialGradient><path fill="url(#SVGOoDJfdBX)" class="ytv8vt8np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:alien-monster" /></template>
<style>
.ab39lr_6o {
  fill: var(--svg-color--995aa8, #995aa8);
  d: path("M30.47 104.24h13.39v13.39H30.47zm53.57 0h13.39v13.39H84.04z");
}

.dmfxm5bje {
  stop-color: var(--svg-color--a363b2, #a363b2);
}

.ibbi6dl4m {
  stop-color: var(--svg-color--b574c3, #b574c3);
}

.ssqyoqd7n {
  d: path("M97.46 64.08V37.3H84.04V23.9H70.65v13.4H57.26V23.9H43.87v13.4H30.48v26.78H17.09v13.39h13.39v13.4h13.39v13.38h13.39V90.87h13.39v13.38h13.39V90.87h13.42v-13.4h13.37V64.08zm-40.21 0H43.86V50.69h13.39zm26.78 0H70.64V50.69h13.39z");
}

.wqx1tjbaj {
  stop-color: var(--svg-color--995aa8, #995aa8);
}

.y13upsbyp {
  stop-color: var(--svg-color--b070bf, #b070bf);
}

.y9j5_d_2r {
  d: path("M110.82 37.29h13.4v26.8h-13.4z");
}

.ytv8vt8np {
  d: path("M3.7 37.28h13.4v26.8H3.7z");
}

.z9t7_xbju {
  fill: var(--svg-color--b574c3, #b574c3);
  d: path("M30.48 10.51h13.39V23.9H30.48zm53.56 0h13.39V23.9H84.04z");
}

</style>
