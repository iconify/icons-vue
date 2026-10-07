<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah8o-2biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah8o-2biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:gas" /></template>
