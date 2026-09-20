<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3vd6dxms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:computer-sound-outline" /></template>
<style>
.a3vd6dxms {
  fill: currentColor;
  d: path("M4 16.462v-11zm-2.23 3v-1h20.46v1zm17.194-2H4.615q-.691 0-1.153-.463T3 15.846V6.077q0-.69.463-1.153t1.152-.462h14.368l-1 1H4.616q-.231 0-.424.192T4 6.077v9.77q0 .23.192.422t.423.193h13.348zm-1.004-4.035l-.72-.72q.339-.37.52-.82t.182-.926t-.182-.926t-.52-.82l.72-.719q.478.517.73 1.15q.252.631.252 1.315q0 .685-.251 1.317q-.252.631-.731 1.149m2.142 2.142l-.708-.708q.781-.78 1.193-1.79t.413-2.11t-.413-2.109t-1.193-1.79l.708-.708q.921.915 1.41 2.098t.488 2.51t-.488 2.51q-.489 1.182-1.41 2.097");
}

</style>
