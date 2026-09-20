<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4corzddk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4corzddk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-right-rhombus-filled" /></template>
