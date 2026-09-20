<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="tleuvtcsl"/><path class="aunr63c_w"/></g><g class="y9tr6bcfx"><path class="w4erq0gmi"/><path class="jlyow4bty"/></g><path class="jbbk7cbmo"/><path class="xo99wi-7x"/><path class="wrnowwb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cricfy-tv" /></template>
<style>
.aunr63c_w {
  d: path("M39.941 18.927q.51-.278 1.04-.522m-3.968 2.574q.445-.4.922-.76m-3.242 3.48q.323-.507.689-.977m-2.144 4.243q.163-.585.377-1.134m-.845 4.081q.015-.301.041-.597m1.753 1.368c.382-5.23 3.597-8.85 7.673-10.89M31.08 28.504c.352-5.471 3.793-9.196 8.095-11.21M14.992 27.812l17.925-10.13M15.147 29.9l19.069.688m-4.867-6.504L15.13 28.89l15.067-1.67");
}

.jbbk7cbmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.343 12.689l-3.703 4.567m4.782-5.159a.703.703 0 1 1-1.403.002a.703.703 0 0 1 1.403-.002");
}

.jlyow4bty {
  d: path("M23.736 30.209v1.566a2.05 2.05 0 0 1-2.06 2.05H9.835a2.05 2.05 0 0 1-2.06-2.05V23.76c0-1.136.92-2.05 2.06-2.05h11.84c.856 0 1.587.515 1.899 1.25");
}

.tleuvtcsl {
  d: path("M43.5 23.836c0 3.923-3.171 7.103-7.084 7.103s-7.084-3.18-7.084-7.103s3.172-7.102 7.084-7.102c3.913 0 7.084 3.18 7.084 7.102");
}

.w4erq0gmi {
  d: path("M28.497 20.177a2.97 2.97 0 0 0-2.429-1.25h-9.715q.007-.065.01-.13a1.993 1.993 0 0 0-1.991-1.997c-1.1 0-1.991.894-1.991 1.996q.003.066.01.131H7.483A2.98 2.98 0 0 0 4.5 21.919v11.697a2.98 2.98 0 0 0 2.984 2.991h18.584a2.98 2.98 0 0 0 2.984-2.991V30.4");
}

.wrnowwb0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.1 13.935l2.865 3.45m-2.526-4.045a.703.703 0 1 1-1.405 0a.703.703 0 1 1 1.405 0");
}

.xo99wi-7x {
  fill: currentColor;
  d: path("M6.795 25.173a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m0 2.595a.75.75 0 1 1-.75-.75a.75.75 0 0 1 .75.75m0 2.595a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
