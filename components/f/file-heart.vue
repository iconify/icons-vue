<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km263xb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km263xb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-heart" /></template>
