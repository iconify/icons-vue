<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f083s_zmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:family-star-rounded" /></template>
<style>
.f083s_zmx {
  fill: currentColor;
  d: path("M13.801 14.845q.793-.616 1.16-1.549H9.04q.367.933 1.157 1.55q.79.615 1.8.615q1.012 0 1.805-.616m-3.123-3.248q.322-.327.322-.794t-.327-.789t-.793-.322t-.789.327t-.322.793t.327.789t.793.322t.789-.326m4.23 0q.323-.327.323-.794q0-.466-.327-.788q-.327-.323-.793-.323q-.467 0-.789.327t-.322.793t.327.789t.793.322t.789-.326M8.125 7.092l2.608-3.47q.238-.322.566-.472T12 3t.701.15t.566.471l2.608 3.471l4.02 1.368q.534.18.822.605q.289.426.289.94q0 .237-.07.471t-.228.449l-2.635 3.573l.1 3.83q.025.706-.466 1.189T16.564 20l-.454-.056L12 18.733l-4.11 1.211q-.124.05-.24.053q-.117.003-.214.003q-.665 0-1.15-.483t-.459-1.188l.1-3.856l-2.629-3.548q-.159-.217-.229-.453Q3 10.236 3 10q0-.506.297-.942q.296-.435.828-.618z");
}

</style>
