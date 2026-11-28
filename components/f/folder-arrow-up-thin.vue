<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy18rac_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="sy18rac_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:folder-arrow-up-thin" /></template>
