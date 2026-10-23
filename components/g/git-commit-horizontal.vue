<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb1v_judf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb1v_judf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:git-commit-horizontal" /></template>
