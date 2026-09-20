<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1hgg5bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1hgg5bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-dot-sharp-fill" /></template>
