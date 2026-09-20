<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="w9n05xn5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-sync-28-filled" /></template>
<style>
.w9n05xn5p {
  fill: currentColor;
  d: path("M21.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13M14.79 3c-.428.49-.75 1.08-.93 1.738L9.162 22.055a.751.751 0 0 0 1.448.393l4.699-17.317A2.89 2.89 0 0 1 18.094 3h.023a3.25 3.25 0 0 1 2.815 1.625l4.764 8.25c.28.487.364 1.053.252 1.587A7.47 7.47 0 0 0 21.499 13c-1.98 0-3.78.768-5.12 2.02l2.463-9.073a.75.75 0 0 0-1.448-.392l-4.698 17.314A2.89 2.89 0 0 1 9.91 25h-.03a3.25 3.25 0 0 1-2.816-1.625L2.3 15.125a2.25 2.25 0 0 1 0-2.25l5.052-8.75A2.25 2.25 0 0 1 9.3 3zm2.71 18a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 1 0v-.814a4 4 0 0 0 2.7 1.984a4 4 0 0 0 3.63-1.09a.5.5 0 0 0-.708-.708A3 3 0 0 1 18.773 22h.727a.5.5 0 0 0 0-1zm4.801-4.669a4 4 0 0 0-3.63 1.09a.5.5 0 0 0 .707.708a3.003 3.003 0 0 1 4.043-.183A3 3 0 0 1 24.227 19H23.5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-1 0v.814a4 4 0 0 0-2.699-1.983");
}

</style>
