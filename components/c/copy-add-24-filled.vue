<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcp9oqbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-add-24-filled" /></template>
<style>
.gcp9oqbdt {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m0 1.999a.5.5 0 0 0-.5.5V17h-2.505a.5.5 0 0 0 0 1h2.506v2.504a.5.5 0 0 0 1 0V18h2.496a.5.5 0 0 0 0-1H18v-2.501a.5.5 0 0 0-.5-.5m-9-.249a4.25 4.25 0 0 0 2.503 3.874a6.46 6.46 0 0 0 .968 3.292a3.3 3.3 0 0 1-.721.084h-5A3.25 3.25 0 0 1 3 17.75v-7.5A3.25 3.25 0 0 1 6.25 7H8.5zM17.75 3A3.25 3.25 0 0 1 21 6.25v5.774a6.502 6.502 0 0 0-9.929 4.509A3.25 3.25 0 0 1 9.5 13.75v-7.5A3.25 3.25 0 0 1 12.75 3z");
}

</style>
