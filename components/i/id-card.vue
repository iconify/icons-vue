<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kutx4ubdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="kutx4ubdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:id-card" /></template>
