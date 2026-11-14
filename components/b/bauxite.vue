<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea_gvkbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bauxite" /></template>
<style>
.ea_gvkbdu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.221 17.226q-.251 1.167.5 2.095q.75.929 1.944.929h14.956q1.088 0 1.83-.797q.741-.796.663-1.881l-.339-4.746q-.039-.542-.299-1.019l-2.555-4.684q-.375-.689-1.076-1.039l-3.888-1.945q-.888-.444-1.838-.158l-3.697 1.11q-.215.064-.408.159q.114.002.222.038t.2.102t.161.156q.069.091.108.198l1.856 5.103l4.586.918q.073.014.141.042t.129.07t.114.093q.052.053.093.114t.069.13q.028.068.043.14t.014.147t-.015.146q-.014.073-.042.141t-.07.129t-.093.114q-.053.052-.114.093t-.13.069q-.068.028-.14.043t-.147.014t-.146-.015l-5-1q-.095-.019-.182-.061q-.086-.042-.16-.105q-.073-.063-.128-.142q-.055-.08-.088-.171l-2-5.5q-.078-.214-.023-.435q-.142.162-.26.354l-3.493 5.676q-.225.365-.315.786z");
}

</style>
