<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="yqfvb1bwf"/><circle class="f934iu1fb"/><path class="y_ptlabie"/><path class="ke-ms6bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:four-oclock" /></template>
<style>
.f934iu1fb {
  cx: 18px;
  cy: 18px;
  r: 14px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

.ke-ms6bzx {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M26.66 23a1 1 0 0 1-1.365.367l-7.795-4.5a.999.999 0 1 1 1-1.732l7.795 4.5A1 1 0 0 1 26.66 23");
}

.y_ptlabie {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M19 18a1 1 0 1 1-2 0V7a1 1 0 0 1 2 0z");
}

.yqfvb1bwf {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--99aab5, #99aab5);
}

</style>
