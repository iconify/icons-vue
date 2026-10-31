<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejzu5je1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejzu5je1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:infinity-duotone-round" /></template>
