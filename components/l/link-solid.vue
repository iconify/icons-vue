<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaf20sbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaf20sbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:link-solid" /></template>
