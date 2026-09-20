<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqxh4ky4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqxh4ky4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:aperture" /></template>
