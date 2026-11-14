<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr4z2jb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:counting-fingers" /></template>
<style>
.tr4z2jb6o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 14v1q0 7.25 5.75 7.25q6.25 0 6.25-7.25V6.25q0-2.5-2.5-2.5q-.573 0-1.015.131q-.178-2.13-2.485-2.13t-2.485 2.13Q9.323 3.75 8.75 3.75q-2.5 0-2.5 2.5zq0-.07.013-.139t.038-.134t.063-.124t.084-.111t.104-.093q.056-.042.118-.073q.063-.03.131-.049q.067-.019.137-.024q5.786-.483 7.483 2.912q.033.066.052.137q.02.071.025.145t-.004.147t-.032.143t-.06.134t-.085.12t-.107.101t-.125.079q-.133.067-.282.077q-.149.011-.29-.036q-.142-.048-.254-.145q-.113-.098-.18-.232q-1.243-2.485-6.017-2.088q-.148.013-.29-.033q-.143-.045-.256-.141q-.114-.097-.183-.229q-.068-.133-.08-.282q-.003-.031-.003-.062");
}

</style>
