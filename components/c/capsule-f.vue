<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6gieobnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-1.5};
const content = `<path class="j6gieobnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:capsule-f" /></template>
