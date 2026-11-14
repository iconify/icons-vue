<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uco9cdazm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bandy-stick" /></template>
<style>
.uco9cdazm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.635 16.4l8.5-13.5q.079-.127.104-.274t-.008-.292q-.033-.146-.119-.267t-.212-.202q-.063-.039-.132-.065t-.142-.039t-.146-.011t-.146.019t-.14.046t-.127.073q-.061.043-.112.096q-.05.054-.09.116l-8.5 13.5Q7.175 19.25 5 19.25q-.59 0-.735-.388q-.155-.412.265-.832q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.105-.106-.243-.163T4 16.75t-.287.057t-.243.163q-1.103 1.103-.61 2.418Q3.371 20.75 5 20.75q3.025 0 5.635-4.35M14.25 18q0-2.75 2.75-2.75T19.75 18T17 20.75T14.25 18");
}

</style>
