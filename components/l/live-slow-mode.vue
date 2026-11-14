<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkapcdb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:live-slow-mode" /></template>
<style>
.bkapcdb-o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.75Q3.25 2.75 3.25 6v8q0 3.122 3 3.245V20q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H17.5q3.25 0 3.25-3.25V6q0-3.25-3.25-3.25zm3 3h5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .24-.14.436L12.922 10l2.188 3.064q.14.196.14.436q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5q-.24 0-.436-.14q-.06-.043-.111-.096q-.05-.054-.089-.117t-.066-.132q-.026-.069-.038-.142t-.01-.146t.019-.146t.047-.139q.031-.068.074-.128L11.078 10L8.89 6.936q-.043-.06-.074-.128q-.03-.067-.047-.139q-.016-.072-.019-.146q-.002-.073.01-.146t.038-.142t.066-.132q.039-.063.089-.117q.051-.053.111-.096q.196-.14.436-.14");
}

</style>
