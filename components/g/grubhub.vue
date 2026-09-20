<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_5v4t7wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_5v4t7wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:grubhub" /></template>
