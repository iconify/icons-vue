<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tefn1vb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:explore-nearby-outline-sharp" /></template>
<style>
.tefn1vb9z {
  fill: currentColor;
  d: path("M8.493 20.292q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709t-3.51-.708M12 16.154q.856-.856 1.513-1.755q.564-.768 1.035-1.705q.471-.936.471-1.837q0-1.238-.887-2.124T12 7.846t-2.132.887t-.886 2.132q0 .893.474 1.826t1.045 1.715q.644.892 1.5 1.748m-.803-4.484q-.331-.331-.331-.803t.33-.804t.803-.332t.804.33t.331.803t-.33.804t-.803.332t-.804-.33");
}

</style>
