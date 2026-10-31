<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmbafvbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmbafvbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ambulance-fill-round" /></template>
