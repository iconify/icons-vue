<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":257};
const content = `<defs><linearGradient id="SVGb4RBMc5u" x1="50%" x2="50%" y1="0%" y2="99.997%"><stop offset="0%" class="x4jvmac5h"/><stop offset="100%" class="q6y0c2ctz"/></linearGradient><linearGradient id="SVGUg4UFeQR" x1="49.997%" x2="49.997%" y1="99.999%" y2=".001%"><stop offset="0%" class="zuql5-b7i"/><stop offset="100%" class="f61ff0fyr"/></linearGradient></defs><path fill="url(#SVGb4RBMc5u)" transform="matrix(1 0 0 -1 0 237.86)" class="h8q044wze"/><path fill="url(#SVGUg4UFeQR)" transform="matrix(1 0 0 -1 0 274.431)" class="kgjkrjt6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:flattr" /></template>
<style>
.f61ff0fyr {
  stop-color: var(--svg-color--6cb02f, #6cb02f);
}

.h8q044wze {
  d: path("M91.794 237.86C31.02 237.86 0 202.797 0 137.335V0l59.535 59.692v69.763c0 27.12 7.175 44.377 31.246 48.252c8.41 1.647 25.91 1.07 37.038 1.07v-41.423c0-.378.051-1.052.148-1.398c.466-1.677 1.98-2.905 3.774-2.909c1.015-.002 1.965.526 2.944 1.493l103.172 103.303l-69.253.016z");
}

.kgjkrjt6a {
  d: path("M196.2 196.453V126.69c0-27.12-7.177-44.38-31.246-48.254c-8.41-1.645-25.91-1.068-37.038-1.068v41.421c0 .376-.051 1.052-.148 1.398c-.466 1.679-1.98 2.906-3.774 2.91c-1.015.003-1.965-.527-2.944-1.492L17.877 18.303l69.254-.016h76.81c60.775 0 91.794 35.06 91.794 100.52v137.337z");
}

.q6y0c2ctz {
  stop-color: var(--svg-color--fabd1f, #fabd1f);
}

.x4jvmac5h {
  stop-color: var(--svg-color--ea5f29, #ea5f29);
}

.zuql5-b7i {
  stop-color: var(--svg-color--abd33c, #abd33c);
}

</style>
