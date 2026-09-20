<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="g1vmz7rvk"/><path class="ldehsby_l"/><path class="gyw3m_b9c"/><path class="etbri8bke"/><path class="dut0bh7qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-antigua-and-barbuda" /></template>
<style>
.dut0bh7qw {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("m29.077 15l-4.154 6L18 31h14a4 4 0 0 0 4-4V9c0-.995-.366-1.903-.967-2.603zM6.923 15L.967 6.397A3.98 3.98 0 0 0 0 9v18a4 4 0 0 0 4 4h14l-6.923-10z");
}

.etbri8bke {
  fill: var(--svg-color--0072c6, #0072c6);
  d: path("M10.279 15H6.923l4.154 6h13.846l4.154-6h-3.356z");
}

.g1vmz7rvk {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.077 21L18 31l6.923-10z");
}

.gyw3m_b9c {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("m25.826 14.978l-3.988-.827l3.392-2.417l-3.976.889l2.28-3.64l-3.36 2.47l.821-4.308l-2.232 3.676L18 6.5l-.763 4.321l-2.232-3.676l.821 4.308l-3.36-2.47l2.28 3.64l-3.976-.889l3.392 2.417l-3.988.827l.105.022h15.442z");
}

.ldehsby_l {
  fill: var(--svg-color--141414, #141414);
  d: path("m10.279 15l-.105-.022l3.988-.827l-3.392-2.417l3.977.889l-2.28-3.64l3.36 2.47l-.821-4.308l2.232 3.675L18 6.5l.763 4.321l2.232-3.675l-.821 4.308l3.36-2.47l-2.28 3.64l3.977-.889l-3.392 2.417l3.988.827l-.106.021h3.356l5.956-8.603A3.99 3.99 0 0 0 32 5H4A3.99 3.99 0 0 0 .967 6.397L6.923 15z");
}

</style>
