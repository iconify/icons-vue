<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boow2abii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boow2abii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-checkered" /></template>
