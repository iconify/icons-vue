<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbfdtibra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bath-salts" /></template>
<style>
.bbfdtibra {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.581 6.211l-.404 1.884l-3.505-.825q-.068-.016-.137-.019q-.07-.003-.139.006t-.135.032t-.126.056t-.115.078q-.053.045-.098.099q-.044.053-.078.114t-.056.127L4.459 11.75H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146q0 4.03 2.866 6.676Q7.905 21.75 12 21.75t6.884-2.574Q21.75 16.53 21.75 12.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 11.75h-2.1q.044-.147.076-.309l.413-2.058q.145-.73-.174-1.403L17.73 4.844q-.828-1.748-2.681-1.192l-2.914.875q-1.276.382-1.554 1.684M6.995 8.887l2.868.675l-.207.967q-.14.652.067 1.221H6.041z");
}

</style>
