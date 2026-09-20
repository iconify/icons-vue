<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9sl6v05z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9sl6v05z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:check-diamond-solid" /></template>
