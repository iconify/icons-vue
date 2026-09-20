<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhacev20g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhacev20g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:blender-filled" /></template>
