<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="gld6by_sh"/><path class="q-fe8qbmg"/><path class="p2_f79b-r"/><path class="s-8r1ccsc"/><path class="gh2qenark"/><path class="y_ar4mbns"/><path class="zxckogb4e"/><path class="ejmw08wxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-pride-48-filled" /></template>
<style>
.ejmw08wxc {
  d: path("M11.25 8C10.56 8 10 8.56 10 9.25v29.5a1.25 1.25 0 1 0 2.5 0V29h24.25c.69 0 1.25-.56 1.25-1.25V9.25C38 8.56 37.44 8 36.75 8h-25.5zM35.5 26.5h-23v-16h23v16z");
  fill: var(--svg-color--212121, #212121);
}

.ft5dv1b6b {
  fill: none;
}

.gh2qenark {
  fill: var(--svg-color--61bc51, #61BC51);
  d: path("M12 20h24v3H12z");
}

.gld6by_sh {
  fill: var(--svg-color--745125, #745125);
  d: path("M12 10h24v2H12z");
}

.p2_f79b-r {
  fill: var(--svg-color--f36d38, #F36D38);
  d: path("M12 14h24v3H12z");
}

.q-fe8qbmg {
  fill: var(--svg-color--e62c46, #E62C46);
  d: path("M12 12h24v2H12z");
}

.s-8r1ccsc {
  fill: var(--svg-color--ffd23e, #FFD23E);
  d: path("M12 17h24v3H12z");
}

.y_ar4mbns {
  fill: var(--svg-color--1793e8, #1793E8);
  d: path("M12 23h24v2H12z");
}

.zxckogb4e {
  fill: var(--svg-color--b73fbb, #B73FBB);
  d: path("M12 25h24v3H12z");
}

</style>
