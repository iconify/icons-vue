<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnk28nxih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnk28nxih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:list-ul" /></template>
