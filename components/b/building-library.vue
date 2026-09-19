<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msl9otbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msl9otbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-library" /></template>
