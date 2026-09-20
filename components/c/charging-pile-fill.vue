<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga33f30at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ga33f30at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:charging-pile-fill" /></template>
