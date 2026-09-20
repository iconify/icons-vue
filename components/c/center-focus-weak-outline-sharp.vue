<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo26vhb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:center-focus-weak-outline-sharp" /></template>
<style>
.eo26vhb7f {
  fill: currentColor;
  d: path("M4 20v-5h1v4h4v1zm11 0v-1h4v-4h1v5zM4 9V4h5v1H5v4zm15 0V5h-4V4h5v5zm-9.123 5.123Q9 13.246 9 12t.877-2.123T12 9t2.123.877T15 12t-.877 2.123T12 15t-2.123-.877m3.536-.71Q14 12.825 14 12t-.587-1.412T12 10t-1.412.588T10 12t.588 1.413T12 14t1.413-.587M12 12");
}

</style>
