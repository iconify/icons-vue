<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptelx9q7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:acorn" /></template>
<style>
.ptelx9q7i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.096 3.78q7.154.4 7.154 6.22q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.75v1.75q0 6.464-6.415 9.671q-.078.039-.163.059t-.172.02t-.172-.02t-.163-.059Q5.25 18.964 5.25 12.5v-1.75H4.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q3.75 10.074 3.75 10q0-6.054 7.74-6.244l.814-2.035q.027-.068.067-.13t.092-.115t.113-.094t.129-.071t.14-.045t.146-.016t.146.013t.142.041q.138.055.245.159t.165.242t.061.286t-.054.288zM6.75 10.75v1.75q0 5.368 5.25 8.156q5.25-2.788 5.25-8.156v-1.75z");
}

</style>
