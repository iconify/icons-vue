<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p10y85byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:computer-sound" /></template>
<style>
.p10y85byy {
  fill: currentColor;
  d: path("M4.616 17.462q-.691 0-1.153-.463T3 15.846V6.077q0-.69.463-1.153t1.152-.462h14.368L15.5 7.944v6.048l3.464 3.47zm-2.847 2v-1h20.462v1zm18.333-3.893l-.708-.708q.781-.78 1.194-1.79t.412-2.11t-.413-2.109t-1.193-1.79l.708-.708q.921.915 1.41 2.098t.488 2.51t-.488 2.51q-.489 1.182-1.41 2.097m-2.142-2.142l-.72-.72q.339-.37.52-.82t.182-.925t-.182-.926t-.52-.82l.72-.72q.478.517.73 1.15q.252.631.252 1.316q0 .684-.251 1.316q-.252.632-.731 1.149");
}

</style>
