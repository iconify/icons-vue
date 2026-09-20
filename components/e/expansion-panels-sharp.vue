<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpgpn5bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:expansion-panels-sharp" /></template>
<style>
.rpgpn5bpo {
  fill: currentColor;
  d: path("M12 17.308L15.308 14l-.714-.713L12 15.88l-2.594-2.594l-.714.713zm-2.594-6.594L12 8.119l2.594 2.594l.714-.713L12 6.692L8.692 10zM4 20V4h16v16z");
}

</style>
