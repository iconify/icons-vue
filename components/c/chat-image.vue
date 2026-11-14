<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9b7qvbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-image" /></template>
<style>
.c9b7qvbsr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 6q0-3.25 3.25-3.25h11q3.25 0 3.25 3.25v8q0 3.25-3.25 3.25h-6.218l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.755q-3-.123-3-3.245zM13.5 7.75q0 2 2 2t2-2t-2-2t-2 2m-6.53 4.72q-.106.105-.163.243T6.75 13t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094L11 10.561l2.97 2.969q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-3.5-3.5q-.105-.106-.243-.163T11 8.75t-.287.057t-.243.163z");
}

</style>
