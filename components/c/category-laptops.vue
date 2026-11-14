<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk88n8bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-laptops" /></template>
<style>
.wk88n8bvi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.375 2.75H6.625q-3.375 0-3.375 3.375v6.75q0 1.185.416 1.954q-.213.106-.326.315l-1.75 3.25q-.045.083-.068.174q-.211.846.19 1.382q.413.55 1.288.55h18q.875 0 1.288-.55q.401-.536.19-1.382q-.023-.091-.068-.174l-1.75-3.25q-.113-.209-.326-.315q.416-.769.416-1.954v-6.75q0-3.375-3.375-3.375");
}

</style>
