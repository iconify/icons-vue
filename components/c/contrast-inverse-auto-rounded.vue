<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skydbebrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contrast-inverse-auto-rounded" /></template>
<style>
.skydbebrq {
  fill: currentColor;
  d: path("M3 12q0-3.354 2.125-5.822t5.317-3.041q.214-.037.385.082q.171.12.208.333t-.083.375t-.333.198q-2.786.5-4.703 2.68Q4 8.988 4 12q0 3.267 2.186 5.505t5.314 2.478v-5.79q0-.349.23-.578q.23-.23.578-.23h7.496q.429 0 .696.332t.148.756q-.8 2.844-3.177 4.686Q15.094 21 12 21q-1.864 0-3.506-.71q-1.642-.711-2.857-1.926q-1.216-1.216-1.926-2.858Q3 13.864 3 12m12.38-3.538l-.884 2.227q-.062.14-.171.226t-.27.085q-.263 0-.4-.205t-.045-.437l3.127-8.137q.042-.102.129-.162Q16.952 2 17.06 2h.265q.108 0 .194.06t.129.161l3.166 8.118q.092.251-.055.456t-.411.205q-.16 0-.279-.076t-.18-.236l-.885-2.227zm.297-.812h3.03l-1.495-3.996h-.077z");
}

</style>
