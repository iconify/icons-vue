<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><radialGradient id="SVGKrceHeYR" cx="50%" cy="50.002%" r="50.004%" fx="50%" fy="50.002%" gradientTransform="scale(1 .99985)"><stop offset="0%" class="dk8d3t44m"/><stop offset="100%" class="stui2mbih"/></radialGradient></defs><path class="rk8n59jtv"/><path class="picxr3vbg"/><path class="rv2ov3bqa"/><path class="shllgjboz"/><path class="yh0agxb-f"/><path class="bm5m5iblf"/><path class="w-o12rbkl"/><path fill="url(#SVGKrceHeYR)" class="zo5qx58gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:dart" /></template>
<style>
.bm5m5iblf {
  fill: var(--svg-color--263238, #263238);
  d: path("M254.325 104.418v104.417h-45.471l1.675 1.694H256V106.093z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dk8d3t44m {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.1;
}

.picxr3vbg {
  fill: var(--svg-color--40c4ff, #40c4ff);
  d: path("M202.116 52.209L158.32 8.413C154.5 4.573 146.538 0 139.8 0c-5.796 0-11.48 1.167-15.15 3.369L43.815 43.796zM104.418 256h106.111v-45.471l-79.16-25.276l-72.422 25.276z");
}

.rk8n59jtv {
  fill: var(--svg-color--01579b, #01579b);
  d: path("M52.209 203.791L8.413 159.995C3.218 154.67 0 147.141 0 139.782c0-3.407 1.92-8.733 3.369-11.782l40.427-84.204z");
}

.rv2ov3bqa {
  fill: var(--svg-color--29b6f6, #29b6f6);
  d: path("M43.796 180.209c0 13.513 1.694 16.826 8.413 23.582l6.738 6.738h151.582l-74.097-84.204l-92.636-82.53z");
}

.shllgjboz {
  fill: var(--svg-color--01579b, #01579b);
  d: path("M178.534 43.777H43.796L210.529 210.51H256V106.093L202.097 52.19c-7.566-7.585-14.285-8.413-23.563-8.413");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.w-o12rbkl {
  fill: var(--svg-color--fff, #fff);
  d: path("M202.116 52.209c-8.356-8.357-15.188-8.413-25.257-8.413H43.815l1.675 1.675h131.369c5.025 0 17.71-.847 25.257 6.738");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yh0agxb-f {
  fill: var(--svg-color--fff, #fff);
  d: path("M53.903 205.466c-6.738-6.756-8.413-13.419-8.413-25.257V45.47l-1.675-1.675v136.413c-.02 11.838-.02 15.113 10.088 25.257l5.044 5.044z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zo5qx58gq {
  d: path("m254.325 104.418l-52.209-52.21L158.32 8.414C154.5 4.573 146.538 0 139.8 0c-5.796 0-11.48 1.167-15.15 3.369L43.815 43.796L3.388 128c-1.45 3.068-3.37 8.394-3.37 11.782c0 7.359 3.238 14.868 8.414 20.213l40.351 40.07c.96 1.185 2.09 2.39 3.426 3.726l1.675 1.675l5.044 5.044l43.796 43.796l1.675 1.675H210.49v-45.47h45.471V106.092z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
