<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcj7e4vyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcj7e4vyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:briefcase-solid" /></template>
