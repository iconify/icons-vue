<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf4qkte-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf4qkte-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ai-gateway" /></template>
