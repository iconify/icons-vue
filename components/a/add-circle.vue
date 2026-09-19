<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tueq-lb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tueq-lb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:add-circle" /></template>
