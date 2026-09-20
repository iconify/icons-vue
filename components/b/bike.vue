<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j41oynb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j41oynb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bike" /></template>
