<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esokwfb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:contrail" /></template>
<style>
.esokwfb9b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m21.006 5.434l.088-.439q.142-.709-.369-1.22t-1.22-.369l-.439.088q-.668.133-1.149.615l-.901.901q-.273.273-.654.209l-2.987-.498q-.874-.146-1.5.479q-.399.397-.321.955q.077.557.569.83l1.871 1.039q.002.001.002.003v.003l-.27.268q-.219.22-.529.22h-.44q-.795 0-1.025.761q-.23.76.431 1.201l.064.043q-6.134 2.584-9.889 9.624q-.07.132-.084.28q-.015.149.028.291q.044.143.139.258q.094.116.226.186t.28.084q.149.015.291-.028q.143-.044.258-.139q.116-.094.186-.226q3.725-6.984 9.878-9.235l.48.719q.441.661 1.201.431q.761-.23.761-1.025v-.439q0-.311.221-.532l.267-.267q.001-.002.003-.001q.002 0 .003.002l1.039 1.871q.273.492.83.569q.558.078.954-.32q.626-.627.48-1.5l-.498-2.988q-.064-.381.209-.654l.901-.901q.482-.481.615-1.149");
}

</style>
