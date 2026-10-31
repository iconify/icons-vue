<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcnkzfaxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcnkzfaxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-check-round" /></template>
