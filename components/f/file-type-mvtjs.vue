<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="kuf42lb8e"><path class="x8r3bo3uc"/><path class="ha91qrqnt"/><path class="cz9ayfbgp"/><g class="l5y23ru5w"><path class="cs8h6m-kd"/><path class="n-it-abfp"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-mvtjs" /></template>
<style>
.cs8h6m-kd {
  fill: var(--svg-color--f7df1e, #f7df1e);
  d: path("M16 15.788h14v14H16z");
}

.cz9ayfbgp {
  fill: var(--svg-color--fff, #fff);
  fill-rule: nonzero;
  d: path("m19.285 10.257l-3.833 5.34a1.79 1.79 0 0 1-1.478.766q-.444 0-.829-.203c-.385-.203-.474-.323-.65-.563l-3.854-5.34v8.37H6.667V7.373h.918q.719 0 1.373.338c.654.338.799.537 1.088.935l3.959 5.52l3.928-5.509q.423-.608 1.083-.946c.66-.338.902-.338 1.388-.338h.929v11.254h-2.048z");
}

.ha91qrqnt {
  fill: var(--svg-color--f7394a, #f7394a);
  d: path("M3 2h22v22H3z");
}

.kuf42lb8e {
  fill-rule: evenodd;
  stroke-linejoin: round;
  stroke-miterlimit: 2;
}

.l5y23ru5w {
  fill-rule: nonzero;
}

.n-it-abfp {
  d: path("m17.617 25.205l1.249-.756c.242.428.461.789.987.789c.505 0 .823-.197.823-.964v-5.219h1.534v5.24c0 1.59-.931 2.314-2.291 2.314c-1.228 0-1.941-.636-2.302-1.404m5.427-.164l1.25-.724c.329.538.757.932 1.513.932c.636 0 1.042-.318 1.042-.756c0-.526-.417-.713-1.119-1.02l-.383-.164c-1.108-.472-1.842-1.064-1.842-2.314c0-1.151.877-2.028 2.247-2.028c.976 0 1.678.34 2.182 1.228l-1.195.767c-.263-.471-.548-.657-.987-.657c-.449 0-.734.285-.734.657c0 .461.285.647.942.932l.384.165c1.305.559 2.039 1.129 2.039 2.412c0 1.381-1.085 2.138-2.543 2.138c-1.425 0-2.346-.68-2.796-1.568");
}

.x8r3bo3uc {
  fill: none;
  d: path("M0 0h32v32H0z");
}

</style>
