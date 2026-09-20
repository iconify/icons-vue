<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9aj82bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:award-star-rounded" /></template>
<style>
.x9aj82bsx {
  fill: currentColor;
  d: path("m12 14.052l1.656 1.015q.217.137.441-.022q.224-.158.169-.426l-.443-1.886l1.47-1.264q.21-.186.12-.431q-.09-.246-.363-.27l-1.917-.176l-.76-1.767q-.106-.242-.373-.242t-.373.242l-.76 1.767l-1.917.175q-.273.025-.363.27t.12.432l1.47 1.264l-.442 1.886q-.056.268.168.426q.224.159.441.022zM9.073 19H6.616q-.672 0-1.144-.472T5 17.385v-2.458l-1.79-1.796q-.237-.243-.349-.538T2.75 12t.112-.593t.347-.538L5 9.073V6.616q0-.672.472-1.144T6.616 5h2.457l1.796-1.79q.243-.237.538-.349T12 2.75t.593.112t.538.347L14.927 5h2.458q.67 0 1.143.472q.472.472.472 1.144v2.457l1.79 1.796q.237.243.349.538t.111.593t-.111.593t-.348.538L19 14.927v2.458q0 .67-.472 1.143q-.472.472-1.143.472h-2.458l-1.796 1.79q-.243.237-.538.349T12 21.25t-.593-.111t-.538-.348z");
}

</style>
