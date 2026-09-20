<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="z572i7b7u"/><path clip-rule="evenodd" class="q386v7riz"/><path clip-rule="evenodd" class="qu9xjrbzo"/><path class="h02-afpba"/><path clip-rule="evenodd" class="j7el9bb6k"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:gift-circle" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h02-afpba {
  d: path("M20 14v2H6v-2z");
}

.j7el9bb6k {
  fill-rule: evenodd;
  d: path("M6 9h14a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1m13 11v-9H7v9z");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.q386v7riz {
  fill-rule: evenodd;
  d: path("M13.356 9.998c.978-1.125.222-3.435-1.085-4.57C10.992 4.314 9.2 4.11 8.23 5.225s-.517 2.863.762 3.975c1.48 1.286 3.347 1.968 4.365.797M11.85 8.681a.35.35 0 0 1 .142-.1a1 1 0 0 1-.147-.023c.012.065.013.11.002.126zm-1.548-.99c.388.337.887.644 1.302.795q.137.05.24.072c-.06-.333-.404-1.202-.886-1.621c-.54-.47-1.103-.534-1.22-.399c-.118.135.024.684.564 1.153");
}

.qu9xjrbzo {
  fill-rule: evenodd;
  d: path("M12.886 9.998c-.978-1.125-.222-3.435 1.084-4.57c1.28-1.113 3.073-1.317 4.042-.202c.97 1.115.518 2.863-.761 3.975c-1.48 1.286-3.347 1.968-4.365.797m1.504-1.317a.35.35 0 0 0-.141-.1c.029-.002.082-.009.147-.023c-.012.065-.013.11-.002.126zm1.548-.99c-.387.337-.886.644-1.3.795a2 2 0 0 1-.242.072c.06-.333.404-1.202.886-1.621c.54-.47 1.103-.534 1.22-.399c.118.135-.024.684-.564 1.153");
}

.z572i7b7u {
  d: path("M12 10h2v11h-2z");
}

</style>
