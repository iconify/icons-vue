<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doywix81z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doywix81z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:check-double" /></template>
