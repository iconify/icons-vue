<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqvvlpb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqvvlpb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:checkbox-blank-circle-fill" /></template>
