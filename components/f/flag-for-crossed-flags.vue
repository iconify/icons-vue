<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="xcoq2q-um"/><path class="aqxyesb3x"/><path class="ivl-3sbnx"/><path class="ey31z3bmy"/><path class="w1qjmxbqm"/><path class="d5r-sebcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-crossed-flags" /></template>
<style>
.aqxyesb3x {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M14.1 34.383a.923.923 0 0 1-.897-1.144L20.811 2.32a.923.923 0 1 1 1.793.442L14.996 33.68a.924.924 0 0 1-.896.703");
}

.d5r-sebcw {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M5.752 13.042a3.233 3.233 0 1 0 6.276-1.556a3.233 3.233 0 0 0-6.276 1.556");
}

.ey31z3bmy {
  fill: var(--svg-color--e8eaeb, #e8eaeb);
  d: path("M2.27 18.187c.491 1.981 1.375 2.514 3.356 2.022l11.655-2.887l-3.333-13.448L2.293 6.762C.313 7.253-.221 8.138.27 10.118z");
}

.ivl-3sbnx {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M30.248 13.042a3.232 3.232 0 1 1-6.275-1.555a3.232 3.232 0 0 1 6.275 1.555");
}

.w1qjmxbqm {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M21.9 34.383a.924.924 0 0 1-.896-.703L13.396 2.762a.924.924 0 0 1 1.794-.442l7.607 30.918a.923.923 0 0 1-.897 1.145");
}

.xcoq2q-um {
  fill: var(--svg-color--e8eaeb, #e8eaeb);
  d: path("M33.73 18.187c-.491 1.981-1.376 2.514-3.356 2.022L18.72 17.322l3.332-13.448l11.655 2.888c1.979.491 2.515 1.376 2.023 3.356z");
}

</style>
