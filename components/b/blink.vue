<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="atduepjmo"/><path class="hss4871kk"/><path class="jfg-a7bdi"/></g><path class="pb5fajbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blink" /></template>
<style>
.atduepjmo {
  d: path("M26.332 27.372c-.5.471-1.19.56-2.332.56s-1.831-.089-2.332-.56m11.609-2.346a2.491 2.491 0 1 1-4.981 0a2.491 2.491 0 1 1 4.982 0");
}

.hss4871kk {
  d: path("M32.633 24.221a.966.966 0 1 1-.967-.966c.534 0 .967.433.967.966m-12.929.805a2.491 2.491 0 1 1-4.981 0a2.491 2.491 0 1 1 4.982 0");
}

.jfg-a7bdi {
  d: path("M19.06 24.221a.966.966 0 1 1-1.933 0a.966.966 0 0 1 1.933 0");
}

.pb5fajbmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.618 41.401c-1.494-1.086-1.112-7.351.123-12.028c-3.758-3.053-7.75-7.897-7.18-9.654c.572-1.757 6.648-3.33 11.48-3.587c1.738-4.515 5.11-9.808 6.958-9.808s5.22 5.293 6.96 9.804l.001-.014c4.831.263 10.907 1.836 11.478 3.592s-3.42 6.601-7.172 9.654c1.247 4.677 1.63 10.943.135 12.028s-7.334-1.214-11.39-3.834c-4.059 2.633-9.899 4.933-11.393 3.847");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
