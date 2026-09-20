<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbil6abfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbil6abfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:amphora" /></template>
