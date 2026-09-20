<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_6wnsirs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-link-24-filled" /></template>
<style>
.z_6wnsirs {
  fill: currentColor;
  d: path("M10.23 6.27a8.376 8.376 0 0 1 5.086 14.255l-1.025 1.022a3.25 3.25 0 0 1-4.596 0l-7.248-7.25A3.25 3.25 0 0 1 2.45 9.7l1.022-1.02a8.4 8.4 0 0 1 2.02-1.49a9.4 9.4 0 0 0-.25 2.577q-.183.156-.356.328l-.001.001l-1.022 1.019a1.25 1.25 0 0 0 0 1.768l7.247 7.25c.488.487 1.28.487 1.768 0l1.024-1.022A6.377 6.377 0 0 0 9.36 8.228a5.3 5.3 0 0 1 .87-1.958m-.534-3.816a3.25 3.25 0 0 1 4.6-.001l7.247 7.249a3.25 3.25 0 0 1 .001 4.595l-1.012 1.012v.001a8.4 8.4 0 0 1-2.023 1.492a9.4 9.4 0 0 0 .253-2.58q.181-.155.355-.326l1.012-1.013a1.25 1.25 0 0 0 0-1.767l-7.248-7.25a1.25 1.25 0 0 0-1.768.002l-1.011 1.011a6.377 6.377 0 0 0 4.542 10.883a5.3 5.3 0 0 1-.87 1.957a8.34 8.34 0 0 1-5.086-2.409a8.376 8.376 0 0 1 0-11.845z");
}

</style>
