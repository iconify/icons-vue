<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w09o546yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w09o546yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-arrow-down-sharp" /></template>
