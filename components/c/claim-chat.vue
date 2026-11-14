<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v48653gbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:claim-chat" /></template>
<style>
.v48653gbc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 1.75h15q2.75 0 2.75 2.75v11q0 2.75-2.75 2.75h-9.218l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.75H4.5q-2.75 0-2.75-2.75v-11q0-1.139.805-1.945q.806-.805 1.945-.805m8.25 2.75h-3.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v9.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-7.5q0-.149-.057-.287t-.163-.243v-.001L13.281 4.72h-.001q-.105-.106-.243-.163T12.75 4.5");
}

</style>
