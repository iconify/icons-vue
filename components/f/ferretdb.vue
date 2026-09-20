<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brwddz0uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brwddz0uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ferretdb" /></template>
