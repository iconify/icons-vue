<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik3ovbcew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hemi" /></template>
<style>
.ik3ovbcew {
  fill: var(--svg-color--ff6c15, #ff6c15);
  d: path("M13.725 3.002a.17.17 0 0 0-.195.135l-1.11 6.438h-.84l-1.11-6.438a.17.17 0 0 0-.195-.135c-3.975.779-7.02 4.222-7.26 8.414c0 0-.015.18-.015.27V12c0 4.447 3.135 8.16 7.275 8.983a.17.17 0 0 0 .195-.135l1.11-6.438h.84l1.11 6.453a.17.17 0 0 0 .195.135c3.96-.794 7.005-4.222 7.26-8.414c0 0 .015-.18.015-.27V12c0-4.476-3.12-8.174-7.275-8.998");
}

</style>
