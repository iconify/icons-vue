<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="afpz09hep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-sync-28-regular" /></template>
<style>
.afpz09hep {
  fill: currentColor;
  d: path("M21.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13M13.248 3a.75.75 0 0 1 0 1.5H9.301a.75.75 0 0 0-.65.375L3.6 13.625a.75.75 0 0 0 0 .75l4.887 8.464a1.323 1.323 0 0 0 2.422-.315L15.64 5.083a2.823 2.823 0 0 1 5.168-.672l4.887 8.464c.28.487.364 1.053.252 1.587a7.5 7.5 0 0 0-1.584-.895L19.51 5.161a1.323 1.323 0 0 0-2.422.315l-4.732 17.441a2.823 2.823 0 0 1-5.168.672L2.3 15.125a2.25 2.25 0 0 1 0-2.25l5.052-8.75A2.25 2.25 0 0 1 9.3 3zM17.5 21a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 1 0v-.814a4 4 0 0 0 2.7 1.984a4 4 0 0 0 3.63-1.09a.5.5 0 0 0-.708-.708A3 3 0 0 1 18.773 22h.727a.5.5 0 0 0 0-1zm4.801-4.669a4 4 0 0 0-3.63 1.09a.5.5 0 0 0 .707.708a3.003 3.003 0 0 1 4.043-.183A3 3 0 0 1 24.227 19H23.5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-1 0v.814a4 4 0 0 0-2.699-1.983");
}

</style>
