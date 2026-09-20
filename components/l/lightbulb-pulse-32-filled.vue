<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ai9uv9y6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lightbulb-pulse-32-filled" /></template>
<style>
.ai9uv9y6n {
  fill: currentColor;
  d: path("M20.42 27.287A3.5 3.5 0 0 1 17.01 30h-2.022a3.5 3.5 0 0 1-3.41-2.713L11.28 26h9.438zm-6.795-9.497a2.501 2.501 0 0 0 4.608.328l1.291-2.582l.054.065a2.5 2.5 0 0 0 1.921.899h3.43a10 10 0 0 1-2.295 2.981c-.343.305-.561.646-.64.988L21.18 24H10.82l-.815-3.531c-.079-.342-.297-.683-.64-.988A10 10 0 0 1 7.07 16.5h3.43a2.5 2.5 0 0 0 2.235-1.383zm-.589-10.789a1 1 0 0 1 .913.683l2.235 6.709l1.921-3.84l.064-.109a1 1 0 0 1 1.6-.085l2.2 2.641H25.5a1 1 0 1 1 0 2h-4a1 1 0 0 1-.769-.36l-1.521-1.825l-2.317 4.632a1 1 0 0 1-1.843-.13l-2.155-6.466l-1.472 3.534A1 1 0 0 1 10.5 15h-4a1 1 0 1 1 0-2h3.333l2.244-5.385l.07-.137a1 1 0 0 1 .89-.477M16 2c5.355 0 9.727 4.21 9.987 9.5H22.67l-1.75-2.1a2.5 2.5 0 0 0-4.082.343l-.074.139l-.302.602l-1.09-3.274a2.5 2.5 0 0 0-4.6-.348l-.08.176l-1.86 4.462h-2.82c.26-5.29 4.632-9.5 9.987-9.5");
}

</style>
