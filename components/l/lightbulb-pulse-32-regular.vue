<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="acpwssb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lightbulb-pulse-32-regular" /></template>
<style>
.acpwssb7n {
  fill: currentColor;
  d: path("M9.387 16.5c.373.547.81 1.048 1.304 1.486c.568.504 1.067 1.188 1.262 2.033L12.641 23h6.716l.688-2.981c.195-.845.694-1.529 1.262-2.033a8 8 0 0 0 1.304-1.486h2.318a10 10 0 0 1-2.295 2.981c-.343.305-.561.646-.64.988l-1.573 6.818A3.5 3.5 0 0 1 17.01 30h-2.022a3.5 3.5 0 0 1-3.41-2.713l-1.574-6.818c-.079-.342-.297-.683-.64-.988A10 10 0 0 1 7.07 16.5zm4.14 10.337A1.5 1.5 0 0 0 14.987 28h2.022a1.5 1.5 0 0 0 1.462-1.163L18.895 25h-5.792zM13.036 7a1 1 0 0 1 .912.683l2.235 6.709l1.921-3.84l.064-.109a1 1 0 0 1 1.6-.085l2.2 2.641H25.5a1 1 0 1 1 0 2h-4a1 1 0 0 1-.769-.36l-1.521-1.825l-2.317 4.632a1 1 0 0 1-1.843-.13l-2.155-6.466l-1.472 3.534A1 1 0 0 1 10.5 15h-4a1 1 0 1 1 0-2h3.333l2.244-5.385l.07-.137a1 1 0 0 1 .89-.477M15.998 2c5.355 0 9.727 4.21 9.987 9.5H23.98a7.998 7.998 0 0 0-15.964 0H6.012c.26-5.29 4.632-9.5 9.987-9.5");
}

</style>
