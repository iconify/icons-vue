<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6czjdkai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6czjdkai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bell-plus-solid" /></template>
