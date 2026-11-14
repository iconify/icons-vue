<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imz5ug5hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:employee-award" /></template>
<style>
.imz5ug5hy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.227 4.227Q5.25 6.204 5.25 9t1.977 4.773q.206.206.421.391l-1.382 6.684q-.015.072-.016.146t.013.147t.042.141t.068.13t.093.114q.051.053.113.094q.061.042.129.071t.14.043q.124.026.249.01q.125-.017.238-.073L12 19.339l4.665 2.332q.133.067.282.077q.149.011.29-.036q.142-.048.254-.145q.113-.098.18-.232q.056-.113.073-.238t-.01-.249l-1.382-6.684q.215-.185.421-.391Q18.75 11.796 18.75 9t-1.977-4.773T12 2.25T7.227 4.227m7.779 10.839l.946 4.572l-3.617-1.809q-.078-.039-.163-.059T12 17.75t-.172.02t-.163.059l-3.617 1.809l.946-4.572q1.361.684 3.006.684t3.006-.684");
}

</style>
