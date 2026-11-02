<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnr7gmnxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnr7gmnxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:briefcase-fill" /></template>
