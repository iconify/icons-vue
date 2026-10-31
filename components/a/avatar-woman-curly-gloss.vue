<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y38x4ibjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y38x4ibjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-woman-curly-gloss" /></template>
