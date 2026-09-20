<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4i1pd5cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4i1pd5cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:calender-solid" /></template>
