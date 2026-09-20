<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zibqkacos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zibqkacos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alert-rhombus" /></template>
