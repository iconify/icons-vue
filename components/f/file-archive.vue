<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drn0rjbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drn0rjbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-archive" /></template>
