<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGe4glMelh"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="ry53cub0h"/><path class="peyacibns"/><path clip-rule="evenodd" class="ccwvmlzpa"/></g></mask></defs><circle mask="url(#SVGe4glMelh)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:eye-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ccwvmlzpa {
  fill-rule: evenodd;
  d: path("M13 17a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7m0-5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.peyacibns {
  d: path("M12 6.5a1 1 0 0 1 2 0v3a1 1 0 1 1-2 0zm4.02.304a1 1 0 0 1 1.96.392l-.5 2.5a1 1 0 0 1-1.96-.392zm-6.04 0a1 1 0 0 0-1.96.392l.5 2.5a1 1 0 0 0 1.96-.392zM5.857 7.986a1 1 0 1 0-1.714 1.029l1.5 2.5a1 1 0 1 0 1.714-1.03zm14.286 0a1 1 0 0 1 1.715 1.029l-1.5 2.5a1 1 0 0 1-1.716-1.03z");
}

.ry53cub0h {
  fill-rule: evenodd;
  d: path("M13 19.5c4.897 0 9-2.308 9-5.5s-4.103-5.5-9-5.5s-9 2.308-9 5.5s4.103 5.5 9 5.5m0-9c3.94 0 7 1.722 7 3.5s-3.06 3.5-7 3.5s-7-1.722-7-3.5s3.06-3.5 7-3.5");
}

</style>
