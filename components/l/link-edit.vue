<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btjoujb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btjoujb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:link-edit" /></template>
