<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1ojuppju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-zip-rounded" /></template>
<style>
.x1ojuppju {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.31q.323 0 .628.13q.305.132.522.349L11.596 7h7.789q.69 0 1.153.463T21 8.616v8.769q0 .69-.462 1.153T19.385 19zM14 18h2v-2h2v-2h-2v-2h2v-2h-2V8h-2v2h2v2h-2v2h2v2h-2z");
}

</style>
