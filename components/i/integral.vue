<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9jepp4vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:integral" /></template>
<style>
.g9jepp4vc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.47 5.03q-.86-.859-1.733-.568q-1.057.336-1.242 1.877l-1.501 11.508q-.299 2.492-2.267 3.118q-1.742.581-3.257-.935q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163T7 18.75t.287.057t.243.163q.86.859 1.743.565q1.047-.333 1.233-1.882l1.499-11.492q.3-2.5 2.258-3.123q1.752-.584 3.267.932q.106.105.163.243t.057.287t-.057.287t-.163.243q-.052.053-.113.094t-.13.069t-.141.043T17 5.25t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094");
}

</style>
