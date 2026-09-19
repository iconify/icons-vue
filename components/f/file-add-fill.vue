<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo7wm5voy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zo7wm5voy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:file-add-fill" /></template>
