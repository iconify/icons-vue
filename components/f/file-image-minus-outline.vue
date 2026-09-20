<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba4iaoq0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba4iaoq0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-image-minus-outline" /></template>
