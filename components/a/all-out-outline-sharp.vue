<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj10wxzre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:all-out-outline-sharp" /></template>
<style>
.dj10wxzre {
  fill: currentColor;
  d: path("M4 20v-3.5h1V19h2.5v1zm12.5 0v-1H19v-2.5h1V20zm-8.748-3.752Q6 14.496 6 12t1.752-4.248T12 6t4.248 1.752T18 12t-1.752 4.248T12 18t-4.248-1.752M12 17q2.075 0 3.538-1.463T17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17M4 7.5V4h3.5v1H5v2.5zm15 0V5h-2.5V4H20v3.5zM12 12");
}

</style>
