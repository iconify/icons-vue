<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he05ftlzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="he05ftlzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-meh-solid" /></template>
