<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3eym7b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3eym7b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:edit-2-filled" /></template>
