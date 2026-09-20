<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmji0zbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kmji0zbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:creative-commons-bold" /></template>
