<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ujt3mubdv"/><path clip-rule="evenodd" class="zq267-bjo"/><path clip-rule="evenodd" class="jtvlijbpl"/><path class="q4mcc3b5a"/><path clip-rule="evenodd" class="axxw8fb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:gift" /></template>
<style>
.axxw8fb6c {
  fill-rule: evenodd;
  d: path("M3 6h14a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1m13 11V8H4v9z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.jtvlijbpl {
  fill-rule: evenodd;
  d: path("M9.886 6.998c-.978-1.125-.222-3.435 1.084-4.57c1.28-1.113 3.073-1.317 4.042-.202c.97 1.115.518 2.863-.761 3.975c-1.48 1.286-3.347 1.968-4.365.797m1.504-1.317a.35.35 0 0 0-.141-.1c.029-.002.082-.009.147-.023c-.012.065-.013.11-.002.126zm1.548-.99c-.387.337-.886.644-1.3.795a2 2 0 0 1-.242.072c.06-.333.404-1.202.886-1.621c.54-.47 1.103-.534 1.22-.399c.118.135-.024.684-.564 1.153");
}

.q4mcc3b5a {
  d: path("M17 11v2H3v-2z");
}

.ujt3mubdv {
  d: path("M9 7h2v11H9z");
}

.zq267-bjo {
  fill-rule: evenodd;
  d: path("M10.356 6.998c.978-1.125.222-3.435-1.085-4.57C7.992 1.314 6.2 1.11 5.23 2.225s-.517 2.863.762 3.975c1.48 1.286 3.347 1.968 4.365.797M8.85 5.681a.35.35 0 0 1 .142-.1a1 1 0 0 1-.147-.023c.012.065.013.11.002.126zm-1.548-.99c.388.337.887.644 1.302.795q.137.05.24.072c-.06-.333-.404-1.202-.886-1.621c-.54-.47-1.103-.534-1.22-.399c-.118.135.024.684.564 1.153");
}

</style>
