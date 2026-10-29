<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvxmwx3yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvxmwx3yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:archive-x" /></template>
