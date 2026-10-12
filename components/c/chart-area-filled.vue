<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sozdzcb0a.css';
import '../../css/b/bt5844bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sozdzcb0a"/><path class="bt5844bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chart-area-filled" /></template>
