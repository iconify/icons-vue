<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa8z4qbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1};
const content = `<path class="qa8z4qbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:gps" /></template>
