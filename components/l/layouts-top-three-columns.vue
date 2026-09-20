<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azvqcqbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="azvqcqbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:layouts-top-three-columns" /></template>
