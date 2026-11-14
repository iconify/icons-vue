<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3ako_evg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cufflinks-box" /></template>
<style>
.h3ako_evg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.765 3.353l-1.5 7.5q-.014.067-.015.136V18.5q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75V11q0-.074-.015-.147l-1.5-7.5q-.012-.063-.036-.124q-.023-.06-.056-.115t-.075-.104q-.043-.049-.093-.09q-.049-.041-.106-.073t-.117-.053t-.124-.033q-.063-.011-.128-.011h-15q-.065 0-.128.011q-.064.011-.124.033q-.061.022-.117.053q-.057.032-.106.073q-.05.041-.093.09t-.075.104t-.056.115t-.036.124M12 11q0-.387-.06-.75h.12q-.06.363-.06.75m-1.245 3.005Q12 12.76 12 11q0 1.76 1.245 3.005t3.005 1.245t3.005-1.245T20.5 11q0-1.366-.749-2.421l-.866-4.329H5.115l-.866 4.329Q3.5 9.634 3.5 11q0 1.76 1.245 3.005T7.75 15.25t3.005-1.245M7.75 8q-3 0-3 3t3 3t3-3t-3-3m5.5 3q0-3 3-3t3 3t-3 3t-3-3m-5.5 1.5q-1.5 0-1.5-1.5t1.5-1.5t1.5 1.5t-1.5 1.5m7-1.5q0 1.5 1.5 1.5t1.5-1.5t-1.5-1.5t-1.5 1.5M7.5 11q0 .25.25.25T8 11t-.25-.25t-.25.25m8.75.25q-.25 0-.25-.25t.25-.25t.25.25t-.25.25");
}

</style>
