<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo3t5svif.css';
import '../../css/e/e95pqp9nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo3t5svif"/><path class="e95pqp9nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:creativity-idea-bulb" /></template>
