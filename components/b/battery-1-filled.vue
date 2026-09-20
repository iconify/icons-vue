<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9bgbabwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9bgbabwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-1-filled" /></template>
