<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aytiybc6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aytiybc6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:glasses-outline" /></template>
