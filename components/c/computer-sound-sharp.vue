<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1m6xh53r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:computer-sound-sharp" /></template>
<style>
.l1m6xh53r {
  fill: currentColor;
  d: path("M3 17.462v-13h15.983L15.5 7.944v6.048l3.464 3.47zm-1.23 2v-1h20.46v1zm18.332-3.893l-.708-.708q.781-.78 1.194-1.79t.412-2.11t-.413-2.109t-1.193-1.79l.708-.708q.921.915 1.41 2.098t.488 2.51t-.488 2.51q-.489 1.182-1.41 2.097m-2.142-2.142l-.72-.72q.339-.37.52-.82t.182-.925t-.182-.926t-.52-.82l.72-.72q.478.517.73 1.15q.252.631.252 1.316q0 .684-.251 1.316q-.252.632-.731 1.149");
}

</style>
