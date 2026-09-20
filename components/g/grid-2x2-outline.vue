<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hulqqcxho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hulqqcxho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-outline" /></template>
