<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGXWUihghp)" class="gmdxdwqjy"/><defs><linearGradient id="SVGXWUihghp" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="wlpjn2qoa"/><stop offset="1" class="i8uan0fox"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kar" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gmdxdwqjy {
  d: path("M6.6 9h2.13c.276 0 1.086-.282 2.124-1.266A538 538 0 0 1 15.9 3h4.5l-7.2 6.9l7.14 9.9H16.8l-3-4.2c.384.918.612 3.252-.114 5.4c.18-2.076-.966-4.356-1.188-4.65c-.198-.264-1.248-2.364-1.752-3.378c-.456-1.968 1.596-3.942 2.682-4.68c-1.428-.912-2.7.144-3.156.78c-.816-.108-1.518.456-1.77.75l-2.364 3.342c-.54.78-1.104.834-1.32.762c.444 1.05 1.518.51 1.998.114c.12.792-.222 1.26-.408 1.392a1.49 1.49 0 0 0 1.278-1.158c.18.264.48 1.308.234 3.33A2.7 2.7 0 0 1 6.36 19.8l-.036-.006H3.6V3h3zm2.382 1.83c0-.348.192-1.05.978-1.062c-.066.804-.684 1.044-.978 1.062");
}

.i8uan0fox {
  stop-color: var(--svg-color--f01e52, #f01e52);
}

.wlpjn2qoa {
  stop-color: var(--svg-color--fb3d42, #fb3d42);
}

</style>
