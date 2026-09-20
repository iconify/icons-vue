<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-rmswbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airline-seat-flat-angled-outline-sharp" /></template>
<style>
.i-rmswbbg {
  fill: currentColor;
  d: path("M19.967 15.829L9.704 12.09L11.41 7.4l10.303 3.739zm-7.951-7.162l-1.025 2.82zm7.003 9.756L3.123 12.631l.348-.933l15.896 5.793zm-13.732-8.18q-.616-.616-.616-1.481t.616-1.481t1.48-.616t1.481.616t.616 1.48q0 .866-.616 1.481q-.615.616-1.48.616q-.866 0-1.481-.616m2.26-.699q.317-.315.317-.78t-.315-.781t-.78-.316t-.781.314q-.317.315-.317.78t.315.781t.78.317t.781-.315m3.444 1.944l8.392 3.061l.992-2.83l-8.36-3.05zm-4.204-2.7");
}

</style>
