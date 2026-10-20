<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxmsu3boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxmsu3boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-template" /></template>
