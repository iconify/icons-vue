<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hch_afbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hch_afbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:folder-minus" /></template>
