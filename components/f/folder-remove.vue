<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg4qicc_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg4qicc_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:folder-remove" /></template>
