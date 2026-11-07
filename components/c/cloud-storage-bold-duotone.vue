<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd-dy5b1v.css';
import '../../css/m/m3911cl6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cd-dy5b1v"/><path class="m3911cl6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-storage-bold-duotone" /></template>
