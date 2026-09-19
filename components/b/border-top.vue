<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oup5h469r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oup5h469r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:border-top" /></template>
