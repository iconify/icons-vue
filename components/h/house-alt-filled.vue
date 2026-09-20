<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muph4f-qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muph4f-qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:house-alt-filled" /></template>
