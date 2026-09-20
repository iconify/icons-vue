<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":311};
const content = `<defs><linearGradient id="SVGEobEabCc" x1="0%" x2="100%" y1="118.01%" y2="118.01%"><stop offset="0%" class="kelxgwb6x"/><stop offset="100%" class="o2xzurbwp"/></linearGradient><linearGradient id="SVGMrRN4bVF" x1="0%" x2="100%" y1="118.01%" y2="118.01%"><stop offset="0%" class="lhe638bdi"/><stop offset="100%" class="vd1hlj1zw"/></linearGradient></defs><path fill="url(#SVGEobEabCc)" class="v5ncwrqhm"/><path fill="url(#SVGMrRN4bVF)" class="aigwbbxgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:clickup-icon" /></template>
<style>
.aigwbbxgc {
  d: path("M128.534 79.52L44.45 152.707L5.583 107.176L128.712 0l122.157 107.255l-39.046 45.372z");
}

.kelxgwb6x {
  stop-color: var(--svg-color--7612fa, #7612fa);
}

.lhe638bdi {
  stop-color: var(--svg-color--fa12e3, #fa12e3);
}

.o2xzurbwp {
  stop-color: var(--svg-color--40ddff, #40ddff);
}

.v5ncwrqhm {
  d: path("m0 238.388l47.24-36.553c25.098 33.087 51.764 48.337 81.444 48.337c29.523 0 55.435-15.07 79.401-47.896L256 237.947c-34.582 47.336-77.556 72.346-127.316 72.346c-49.6 0-92.991-24.85-128.684-71.905");
}

.vd1hlj1zw {
  stop-color: var(--svg-color--gold, gold);
}

</style>
