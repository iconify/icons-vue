<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut_e94bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chair-counter" /></template>
<style>
.ut_e94bbl {
  fill: currentColor;
  d: path("M7.789 21v-.673q.823-.587 1.768-.889t1.943-.369v-2.78H8.711v-1H11.5V8.673H9.866q-.443 0-.77-.249t-.419-.655H6.423q-.588 0-1.006-.412T5 6.356q0-1.398.958-2.377T8.288 3h7.443q1.373 0 2.321.989q.948.988.948 2.367q0 .588-.417 1t-.987.413h-2.254q-.13.387-.448.646q-.317.258-.74.258H12.5v6.616h2.789v1H12.5v2.78q.998.068 1.953.37t1.778.888V21z");
}

</style>
