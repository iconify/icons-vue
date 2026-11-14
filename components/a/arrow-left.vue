<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmjcg-30s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-left" /></template>
<style>
.jmjcg-30s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.72 18.78l-6.25-6.25q-.099-.099-.156-.226q-.056-.128-.063-.268L3.25 12q0-.149.057-.287t.163-.243v-.001L9.72 5.22q.105-.106.243-.163T10.25 5t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113l-4.969 4.97H20q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H5.811l4.969 4.97q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163T10.25 19t-.287-.057t-.243-.163");
}

</style>
