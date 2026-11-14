<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8o-82btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hazard-flame" /></template>
<style>
.s8o-82btu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.174 9.614l-5.788-5.788Q12 1.44 9.614 3.826L3.826 9.614q-2.386 2.386 0 4.772l5.788 5.788q2.386 2.386 4.772 0l5.788-5.788q2.386-2.386 0-4.772M12 17.25q-3.75 0-3.75-3.75q0-1.11.757-2.743Q9.75 9.154 9.75 8q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.227 0 .416.126q1.25.834 1.896 1.826q.043-.101.114-.185t.162-.144q.092-.06.197-.092q.105-.031.215-.031q.149 0 .287.057t.243.163q1.72 1.719 1.72 4.53q0 3.75-3.75 3.75");
}

</style>
