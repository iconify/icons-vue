<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svhsbv9cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assignment-late-outline-sharp" /></template>
<style>
.svhsbv9cd {
  fill: currentColor;
  d: path("M12.434 16.318q.182-.181.182-.433t-.182-.434t-.434-.182t-.434.182t-.182.433q0 .252.182.434T12 16.5t.434-.182m-.934-2.78h1V7.462h-1zM4 20V4h6.316q-.137-.766.366-1.383Q11.184 2 12 2q.835 0 1.338.617T13.685 4H20v16zm1-1h14V5H5zm7.538-14.77q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212M5 19V5z");
}

</style>
