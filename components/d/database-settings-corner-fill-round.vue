<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvqpby2ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvqpby2ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-settings-corner-fill-round" /></template>
