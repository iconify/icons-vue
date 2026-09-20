<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu20g6b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu20g6b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clipboard-check-filled" /></template>
