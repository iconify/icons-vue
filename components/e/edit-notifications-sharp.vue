<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6f_0hn_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-notifications-sharp" /></template>
<style>
.t6f_0hn_u {
  fill: currentColor;
  d: path("M12 22q-.825 0-1.412-.587T10 20h4q0 .825-.587 1.413T12 22m-8-3v-2h2v-7q0-2.075 1.25-3.687T10.5 4.2V2h3v2.2q.275.075.538.163t.512.212L10 9.1V15h5.9l2.1-2.1V17h2v2zm8-6V9.925l6.575-6.55l3.075 3.05L15.075 13zm6.575-5.6l.925-.975l-.925-.925l-.95.95z");
}

</style>
