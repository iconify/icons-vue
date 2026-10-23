<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mepfk3yoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mepfk3yoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-sort-descending" /></template>
