<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woho_9h3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woho_9h3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dog" /></template>
