<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-8o074js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-8o074js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:carets-from-axis-vertical" /></template>
