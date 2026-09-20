<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qse-3obuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qse-3obuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:arxiv" /></template>
