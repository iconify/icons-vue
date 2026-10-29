<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgehlxb8p.css';
import '../../css/b/bdn4j9fmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgehlxb8p"/><path class="bdn4j9fmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:chevron-down" /></template>
