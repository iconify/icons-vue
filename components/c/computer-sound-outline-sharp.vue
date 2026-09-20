<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d42o8-b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:computer-sound-outline-sharp" /></template>
<style>
.d42o8-b7i {
  fill: currentColor;
  d: path("M4 16.462v-11zm-2.23 3v-1h20.46v1zm17.194-2H3v-13h15.983l-1 1H4v11h13.964zm-1.004-4.035l-.72-.72q.339-.37.52-.82t.182-.926t-.182-.926t-.52-.82l.72-.719q.478.517.73 1.15q.252.631.252 1.315q0 .685-.251 1.317q-.252.631-.731 1.149m2.142 2.142l-.708-.708q.781-.78 1.193-1.79t.413-2.11t-.413-2.109t-1.193-1.79l.708-.708q.921.915 1.41 2.098t.488 2.51t-.488 2.51q-.489 1.182-1.41 2.097");
}

</style>
