<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oao_oqtzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oao_oqtzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bird" /></template>
