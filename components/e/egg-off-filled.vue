<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp4zsc_7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4zsc_7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:egg-off-filled" /></template>
