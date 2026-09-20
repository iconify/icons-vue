<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya4cjjcke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ya4cjjcke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circles-sharp-fill" /></template>
