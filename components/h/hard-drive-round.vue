<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6my62buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6my62buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-drive-round" /></template>
