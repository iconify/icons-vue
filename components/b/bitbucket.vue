<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q97iszbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bitbucket" /></template>
<style>
.q97iszbiv {
  fill: currentColor;
  d: path("M6.662 19.616q-.359 0-.59-.191q-.232-.19-.296-.55L3.564 5.15q-.05-.34.122-.553q.173-.212.49-.212h15.651q.333 0 .499.211q.166.212.104.551l-.597 3.63q-.062.362-.287.548q-.226.187-.59.187h-9.42q-.017 0-.205.242l.74 4.542q.02.07.212.193h3.409q.085 0 .212-.193l.536-3.275q.043-.296.223-.44t.476-.142h3.705q.333 0 .5.211t.123.529l-1.243 7.696q-.063.36-.295.55t-.59.19z");
}

</style>
