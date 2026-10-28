<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axq2v98iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contrast-auto-rounded" /></template>
<style>
.axq2v98iv {
  fill: currentColor;
  d: path("M12 21q-1.864 0-3.506-.71q-1.642-.711-2.857-1.926q-1.216-1.216-1.926-2.858Q3 13.864 3 12q0-3.083 1.823-5.453t4.637-3.19q.515-.155.852.291t.096.986q-.204.541-.306 1.14T10 7q0 1.627.668 3.012q.669 1.384 1.832 2.334v7.637q2.766-.177 4.826-2.019q2.06-1.841 2.549-4.589q.037-.213.198-.333t.375-.083t.333.208t.083.385q-.555 3.198-3.032 5.323Q15.354 21 12 21m3.38-12.538l-.884 2.226q-.062.14-.171.226t-.27.086q-.263 0-.4-.205t-.045-.437l3.127-8.137q.042-.102.129-.162Q16.952 2 17.06 2h.265q.108 0 .194.06t.129.161l3.166 8.118q.092.251-.055.456t-.411.205q-.16 0-.279-.076t-.18-.236l-.885-2.227zm.297-.812h3.03l-1.495-3.996h-.077z");
}

</style>
