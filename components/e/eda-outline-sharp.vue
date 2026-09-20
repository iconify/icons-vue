<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9_nlcboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:eda-outline-sharp" /></template>
<style>
.p9_nlcboh {
  fill: currentColor;
  d: path("M7.673 11.77v-9h1v9zm3.654 0v-10h1v10zM15 16.112V3.77h1v11.766zM5 21.27h8.806l6.158-6.215l-.5-.385l-8.08 4.771l-3.134-4.17H5zm-1 1v-8h4.75l2.866 3.829L16 15.535l3.842-2.239l1.914 1.412l-7.562 7.561zm1-8H4v-9.5h1zm0-2.5h10zm0 9.5h8.806z");
}

</style>
