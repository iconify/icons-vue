<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fylc7j5wh.css';
import '../../css/r/rn0ksnpzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fylc7j5wh"/><path class="rn0ksnpzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-pen-filled" /></template>
