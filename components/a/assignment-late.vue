<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylnwfi90w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assignment-late" /></template>
<style>
.ylnwfi90w {
  fill: currentColor;
  d: path("M12.434 16.318q.182-.181.182-.433t-.182-.434t-.434-.182t-.434.182t-.182.433q0 .252.182.434T12 16.5t.434-.182m-.934-2.78h1V7.462h-1zM5.616 20q-.667 0-1.141-.475T4 18.386V5.615q0-.666.475-1.14T5.615 4h4.7q-.136-.766.367-1.383Q11.184 2 12.01 2t1.328.617T13.685 4h4.7q.666 0 1.14.475T20 5.615v12.77q0 .666-.475 1.14t-1.14.475zm6.922-15.77q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212");
}

</style>
