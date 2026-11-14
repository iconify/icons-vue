<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd_dbobhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-nurse" /></template>
<style>
.xd_dbobhe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.25q-3.25 0-3.25 3.25v9q0 2.056 1.5 2.77v3.48q0 .132.045.255q.045.124.129.225q.095.115.227.184q.133.069.281.083t.291-.031t.257-.14l4.292-3.576H17.5q3.25 0 3.25-3.25v-9q0-3.25-3.25-3.25zm.265 10.353l1.25-6.25q.012-.063.036-.124q.023-.06.056-.115t.075-.104t.093-.09q.049-.041.106-.073t.117-.053t.124-.033q.063-.011.128-.011h6.5q.065 0 .128.011q.064.011.124.033q.061.022.117.053q.057.032.106.073q.05.041.093.09t.075.104t.056.115q.024.061.036.124l1.25 6.25q.015.072.015.146t-.014.147q-.015.072-.043.14t-.069.13t-.093.114t-.114.093q-.061.041-.129.07q-.068.028-.141.042q-.195.039-.384-.023q-4.263-1.421-8.526 0q-.141.047-.29.036q-.149-.01-.282-.077q-.134-.067-.232-.18q-.097-.112-.145-.254q-.062-.189-.023-.384");
}

</style>
