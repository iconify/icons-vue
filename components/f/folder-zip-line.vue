<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jckk0c03o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jckk0c03o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-zip-line" /></template>
