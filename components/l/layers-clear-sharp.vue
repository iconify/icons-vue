<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czvga6mpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:layers-clear-sharp" /></template>
<style>
.czvga6mpq {
  fill: currentColor;
  d: path("M15.062 12.53L8.596 6.093L12 3.462l7.385 5.73zm2.163 2.159l-.72-.72l2.076-1.592l.804.634zm2.921 7.18l-5.308-5.307L12 18.742l-7.385-5.73l.804-.635L12 17.462l2.1-1.633l-1.425-1.42l-.675.514l-7.385-5.73l1.594-1.26l-4.468-4.458l.713-.713l18.4 18.4z");
}

</style>
