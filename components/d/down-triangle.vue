<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e957222re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e957222re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:down-triangle" /></template>
