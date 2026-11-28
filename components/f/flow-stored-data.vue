<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur_vkvbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur_vkvbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-stored-data" /></template>
