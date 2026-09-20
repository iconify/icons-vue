<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGO7I5vbkq)" clip-rule="evenodd" class="aak9r6b9l"/><defs><linearGradient id="SVGO7I5vbkq" x1="3.219" x2="20.005" y1="12" y2="12.303" gradientUnits="userSpaceOnUse"><stop class="o_q23xbak"/><stop offset="1" class="a8n59lb6r"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bist" /></template>
<style>
.a8n59lb6r {
  stop-color: var(--svg-color--fab242, #fab242);
}

.aak9r6b9l {
  fill-rule: evenodd;
  d: path("M10.734 3.344a2.5 2.5 0 0 1 2.532 0l5.502 3.226a2.5 2.5 0 0 1 1.235 2.161v6.533a2.5 2.5 0 0 1-1.235 2.16l-5.502 3.232a2.5 2.5 0 0 1-2.532 0l-5.502-3.231a2.5 2.5 0 0 1-1.235-2.161V8.73a2.5 2.5 0 0 1 1.235-2.16l5.502-3.232zm-4.236 7.153h.01c.4.155 1.35.515 1.49 2l-.02-.004c-.625-.23-1.43-.526-1.48-1.996m4.001-4.502c-1.305.57-2.25 1.826-2.25 3.076v4.927h.01a4.001 4.001 0 1 0 7.428-2.3a2.85 2.85 0 0 0-2.436-1.201c-2.231 0-2.601 1.28-2.747 1.776l-.005.02zm0 6.303l.12-.07a3.36 3.36 0 0 1 1.616-.506c.76 0 1.766.55 1.766 1.776c0 1.68-1.75 1.75-1.75 1.75s-1.752-.114-1.752-1.61v-1.345z");
}

.ft5dv1b6b {
  fill: none;
}

.o_q23xbak {
  stop-color: var(--svg-color--f68c1e, #f68c1e);
}

</style>
