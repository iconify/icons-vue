<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw7rjbczd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw7rjbczd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-plus-corner-fill-round" /></template>
