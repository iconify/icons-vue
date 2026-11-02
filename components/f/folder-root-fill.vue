<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyl8i9baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyl8i9baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-root-fill" /></template>
