<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awgxgaces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-info-outline" /></template>
<style>
.awgxgaces {
  fill: currentColor;
  d: path("M4 18V6v5.373v-.72zm6.95 1H4.616q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h4.981l2 2h7.789q.69 0 1.153.463T21 8.616v3.413q-.233-.2-.473-.358T20 11.373V8.616q0-.27-.173-.443T19.385 8h-8.19l-2-2h-4.58q-.269 0-.442.173T4 6.615v10.77q0 .269.173.442t.443.173h6.075q.036.275.102.515q.067.24.157.485m8.886-4.836Q21 15.33 21 17t-1.164 2.836T17 21t-2.835-1.164T13 17t1.165-2.835T17 13t2.836 1.165m-3.22 5.374h.768V16.46h-.769zm.734-4.227q.15-.15.15-.35t-.15-.35t-.35-.15t-.35.15t-.15.35t.15.35t.35.15t.35-.15");
}

</style>
