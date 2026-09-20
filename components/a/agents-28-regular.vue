<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="q_6nvtbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-28-regular" /></template>
<style>
.q_6nvtbwq {
  fill: currentColor;
  d: path("M9.303 4.5a.75.75 0 0 0-.65.375l-5.05 8.75a.75.75 0 0 0 0 .75l4.886 8.464a1.322 1.322 0 0 0 2.421-.315l4.733-17.44a2.822 2.822 0 0 1 5.168-.673l4.886 8.464a2.25 2.25 0 0 1 0 2.25l-5.051 8.75A2.25 2.25 0 0 1 18.697 25H14.75a.75.75 0 0 1 0-1.5h3.947a.75.75 0 0 0 .65-.375l5.051-8.75a.75.75 0 0 0 0-.75l-4.886-8.464a1.322 1.322 0 0 0-2.422.315l-4.732 17.44a2.822 2.822 0 0 1-5.168.673l-4.887-8.464a2.25 2.25 0 0 1 0-2.25l5.052-8.75A2.25 2.25 0 0 1 9.303 3h3.947a.75.75 0 0 1 0 1.5z");
}

</style>
