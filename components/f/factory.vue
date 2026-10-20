<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5_uufbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5_uufbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:factory" /></template>
