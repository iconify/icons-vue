<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok4yy0jjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok4yy0jjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:alarm" /></template>
