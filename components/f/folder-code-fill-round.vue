<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac36-yj6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac36-yj6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-code-fill-round" /></template>
