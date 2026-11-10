<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj9l6dm3r.css';
import '../../css/g/gxvh0c--h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj9l6dm3r"/><path class="gxvh0c--h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:grid-3x3-off-filled" /></template>
