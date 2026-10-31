<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3rc2dbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3rc2dbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-close-corner-round" /></template>
