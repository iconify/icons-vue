<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzmvq8bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzmvq8bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:columns-3" /></template>
