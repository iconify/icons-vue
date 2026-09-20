<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py4dlzblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py4dlzblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left-square-filled" /></template>
