<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt7j6mbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt7j6mbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:file" /></template>
