<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya9pjdagh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya9pjdagh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cloud-fog-solid" /></template>
