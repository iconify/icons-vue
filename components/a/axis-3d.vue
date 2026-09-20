<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npvc9kgtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npvc9kgtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:axis-3d" /></template>
