<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0k3o-b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0k3o-b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:joomla" /></template>
