<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1-p9w6au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:content-warning" /></template>
<style>
.l1-p9w6au {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.938 6.424l5.251 9.29q.954 1.687-.023 3.362q-.977 1.674-2.915 1.674H6.749q-1.938 0-2.915-1.674q-.977-1.675-.023-3.362l5.251-9.29Q10.031 4.71 12 4.71t2.938 1.714M12 11.125q-2.935 0-4.651 3.003q-.049.085-.074.179q-.025.095-.025.193t.025.193q.025.094.074.179Q9.065 17.875 12 17.875t4.651-3.003q.049-.085.074-.179q.025-.095.025-.193t-.025-.193q-.025-.094-.074-.179q-1.716-3.003-4.651-3.003");
}

</style>
