<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b383qj07c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b383qj07c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:align-right" /></template>
