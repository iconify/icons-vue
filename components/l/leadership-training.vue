<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0yziacck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leadership-training" /></template>
<style>
.o0yziacck {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 3.75V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014q.094 0 .186.023q.091.024.174.069t.151.109q.069.065.12.144q.377-.066.786.062l.807.252q.985.309.985 1.341t-.985 1.341l-.807.252q-.345.108-.667.078V7q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T10 7.75t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.25 7zM3.288 17.536l4.628-8.33q.691-1.243 2.111-1.285q1.42-.043 2.184 1.156l.954 1.499q.123.195.353.197t.358-.189q.576-.863 1.612-.817t1.533.957l3.725 6.829q.682 1.249-.044 2.473t-2.15 1.224H5.474q-1.43 0-2.155-1.232t-.031-2.482");
}

</style>
