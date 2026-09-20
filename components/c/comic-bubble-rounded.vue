<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn955mbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comic-bubble-rounded" /></template>
<style>
.zn955mbpc {
  fill: currentColor;
  d: path("M18.7 18.7q-.18.18-.416.237q-.236.055-.503-.081l-4.073-2.087l-2.143 2.143q-.242.242-.565.242t-.566-.243L8.514 17H5.808q-.343 0-.576-.232T5 16.192v-2.706l-1.911-1.92q-.243-.243-.243-.566t.242-.565L5 8.514V5.808q0-.343.232-.576T5.808 5h2.706l1.92-1.911q.243-.243.566-.243t.566.243L13.486 5h2.706q.344 0 .576.232t.232.576v2.706l1.912 1.92q.242.243.242.566t-.242.566l-2.143 2.142l2.087 4.073q.136.267.08.503q-.055.235-.236.416");
}

</style>
