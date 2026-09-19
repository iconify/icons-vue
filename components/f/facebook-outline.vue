<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-md56bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-md56bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:facebook-outline" /></template>
