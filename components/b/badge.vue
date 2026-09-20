<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znde4_osf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znde4_osf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:badge" /></template>
