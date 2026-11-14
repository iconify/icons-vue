<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8dauu23o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crescendo" /></template>
<style>
.y8dauu23o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.763 5.288l-17.999 6h-.001q-.049.017-.095.039l-.003.002q-.127.064-.222.169t-.145.238l-.01.027q-.038.115-.038.237t.038.237q.048.142.145.254q.098.113.232.18q.044.022.092.038l.006.003h.001l17.999 6q.07.023.143.032t.147.004t.145-.025q.071-.019.137-.052t.125-.079q.058-.045.107-.101q.048-.055.085-.12q.036-.064.06-.134q.023-.07.032-.143t.004-.147t-.025-.145q-.019-.071-.052-.137t-.079-.125q-.045-.058-.101-.107q-.055-.048-.12-.085q-.064-.036-.134-.06L5.372 12l15.865-5.288q.142-.048.254-.145q.113-.098.18-.232q.067-.133.077-.282q.011-.149-.036-.29q-.024-.07-.06-.134q-.037-.065-.085-.12q-.049-.056-.107-.101q-.059-.046-.125-.079t-.137-.052t-.145-.025t-.147.004t-.143.032");
}

</style>
