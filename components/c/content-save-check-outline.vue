<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlgyd4b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlgyd4b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:content-save-check-outline" /></template>
